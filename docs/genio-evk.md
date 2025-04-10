---
layout: default
title: Genio Evaluation Kits
nav_order: 2
---

# How to Use Your Genio Board?
##### update : 2025/01 by ITRI (EOSL-R3)

<div align="center">
<img src="assets/images/pages/genio_510_evk.png" width="560"/>
</div>

The Genio Evaluation Kits provide a versatile platform for AIoT applications, offering a range of configurations to meet diverse performance and power requirements. Powered by Arm Cortex-A CPUs, Mali GPUs, and MediaTek DLA, these kits support both Yocto and Ubuntu 22.04 operating systems. With scalable performance, flexible memory options, and GPIO interfaces, the Genio series delivers the versatility needed for edge AI solutions, whether requiring high computational power or energy-efficient designs.

### Operating Systems:

* **Yocto**: Known for its high power performance, Yocto is ideal for developers who require a highly customizable and efficient OS. However, it may present a steeper learning curve due to its complexity. Through ITRI's [PinMux tool](), developers can effectively manage hardware pin assignments, enabling the configuration of GPIOs, communication interfaces (such as I2C, SPI, and UART), and other peripheral connections to meet specific application requirements.
* **Ubuntu 22.04**: Known for its user-friendly interface and extensive community support, Ubuntu 22.04 simplifies the development process, making it ideal for developers who prioritize ease of use and rapid prototyping. Its compatibility with Genio chipsets allows for seamless integration of AI frameworks and tools, enabling efficient deployment of AI models and applications without the steep learning curve associated with more customizable operating systems.


### Device Tpye: 

|  Devices     | Genio 510     | Genio 700     | Genio 1200     |
| :----------: |:-------------:|:-------------:|:--------------:|
| **OS**            |  `Yocto`, `Ubuntu 22.04`            |   `Yocto`, `Ubuntu 22.04`            |   `Yocto`, `Ubuntu 22.04`            |
| **CPU**           |  `Cortex-A55`x4,`Cortex-A78`x2      |   `Cortex-A55`x6,`Cortex-A78`x2      |   `Cortex-A55`x4,`Cortex-A78`x4      |
| **GPU**           |  `Mali-G57 MC2`                       |   `Mali-G57 MC3`                   |   `Mali-G57 MC5`                     |
| **APU**           | `MDLA 3.0`x1, `VP`x1                |   `MDLA 3.0`x1, `VP`x1               |   `MDLA 2.0`x2, `VP`x2               |
| **Performance**   | 0.15~2.8TOPs                        | 0.20~4.0TOPs                         | 0.25~4.8TOPs                         |
| **Power**         | 3.5~4.5W                            | 5~6W                                 | 6.2~7.2W                             |
| **Unified Memory**| 4GB LPDDR4                          | 8GB LPDDR4                           | 16GB LPDDR5                          |

Genio 510/700 are ideal for tasks involving single vision-based models with complex structures (e.g., YOLOs). The Genio 700, with its larger memory, supports higher parallel processing capabilities, making it well-suited for streaming media applications. In contrast, the Genio 1200 is optimized for tasks requiring composite models with simpler structures (e.g., ResNet for image classification). You can choose the chipset that best suits your specific requirements.


## AI Development Resources

The diverse chipset of this system provides extensive application potential, while also indicating that software developers will face a more complex development environment.

* First, you need to prepare a workstation for flashing the operating system onto the Genio EVK. This workstation must be an Ubuntu operating system with an x86 or amd64 processor architecture to correctly install and activate the Flash Tools. 
* Secondly, if you wish to accelerate your deep learning models using MTK's DLA or VP, you may need to follow the [NeuronPilot Installation]() guide to additionally install NeuronPilot. 
* This tool helps you compile TFLite-format models into the specific descriptor format required by the accelerator, enabling the use of deep learning accelerators (note that the supported descriptor formats vary depending on the version and model of the processor, and the target processor must be specified based on the board model during compilation). 
* Alternatively, you can choose to use the [Online Version of NeuronPilot](https://app-aihub-neuronpilot.azurewebsites.net/) built by ITRI for the [MTK-Genio-Demo](https://github.com/R300-AI/MTK-genio-demo/tree/main), allowing you to independently perform simple runtime tests on the board.

<div align="center">
<img src="assets/images/pages/genio_510_demonstration_workflow.png" width="780"/>
</div>

The diagram above illustrates the complete system resources and workflow. Once the board is properly set up, model inference can be performed using Native Frameworks, ArmNN, or NeuronRT. 

These environments can be quickly configured by following the guidelines provided in this document. **Native Frameworks (TFLite)** primarily rely on the CPU for inference. **ArmNN** accelerates inference by optimizing both the CPU and GPU, offering faster and more efficient processing compared to running inference without ArmNN, though it requires more memory. 

**NeuronRT** utilizes the MediaTek Deep Learning Accelerator (MDLA) or Vision Processor (VP) to achieve high-performance inference. For practical examples and benchmarks, refer to the [Model Zoo](https://github.com/R300-AI/ITRI-AI-Hub/tree/main/Model-Zoo).

<br>
<div align="right">
<a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/genio-evk/neuronPilot_installation.html"> 

[ Next >> Step1. NeuronPilot Installation ]
  
</a>
</div>
