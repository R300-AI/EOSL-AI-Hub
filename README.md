<div align="center">
  
  [ITRI AI Hub](https://e-aihub.dev/) is an **AI Deployment Verification Platform** build upon selected CPUs, GPUs, NPUs, and MCUs. It is designed to delegate the computer vision (CV), natural language process (NLP), audio signals and multimodal models to be accelerated on-chip. making AI application proof-of-concept and commercial implementation easier.

Contact With Us :wave:

| [Application Validation](mailto:sylvia.chan@itri.org.tw) | [Chipset Partnership](mailto:Markv.chen1996@itri.org.tw) | [Developer Support](mailto:Markv.chen1996@itri.org.tw) |

</div>

## <div align="center">Documentations</div>

<details>
<summary>Arm Raspberry Pi Module</summary>

The Raspberry Pi module is a compact and versatile platform ideal for developing and deploying small-scale, standalone or multi-node AI applications. Powered by **Arm Cortex-A** processors, it supports a wide range of AI development tasks

![](https://img.shields.io/badge/OS-Raspberry_Pi_OS_|_Ubuntu-orange) ![](https://img.shields.io/badge/Python-3.9-green) ![](https://img.shields.io/badge/Framework-TensorFlow_|_PyTorch-blue)
  * [Get Started with Raspberry Pi OS](https://www.raspberrypi.com/documentation/computers/getting-started.html)
  * [Deploy AI Models on Raspberry Pi](https://www.tensorflow.org/lite/guide/python)
  * [ONNX Runtime IoT Deployment on Raspberry Pi](https://onnxruntime.ai/docs/tutorials/iot-edge/rasp-pi-cv.html)

</details>

<details open>
<summary>MediaTek Genio AIoT Module</summary>

The MediaTek Genio module is a high-performance platform designed for AIoT applications, powered by **Arm Cortex-A**, **Arm GPU**, and **MediaTek DLA**. Its **shared memory SoC architecture** enables efficient data exchange, optimizing AI workloads for computer vision, natural language processing, and multimodal applications. With support for General-Purpose I/O (GPIO) interfaces, it is ideal for developing edge AI solutions.

![](https://img.shields.io/badge/OS-Ubuntu_|_Yocto-orange) ![](https://img.shields.io/badge/NeuronPilot-v6-blue) ![](https://img.shields.io/badge/Python-3.7-green)
 
  * [Get Started with IoT Yocto](https://mediatek.gitlab.io/aiot/doc/aiot-dev-guide/master/sw/yocto/get-started.html)
  * [Get Started with Ubuntu on Genio](https://mediatek.gitlab.io/genio/doc/ubuntu/get-started.html)
  * [Deploy Pre-Trained Models using NVIDIA TAO Toolkit](https://mediatek.gitlab.io/genio/doc/tao/index.html)

</details>

<details>
<summary>AMD Ryzen AI PC Module</summary>

AMD Ryzen AI processors are cutting-edge SoCs designed for AI PCs, integrating the powerful **Zen CPU**, **RDNA iGPU**, and **XDNA NPU**. With seamless multi-chip synchronization, they deliver up to **50 TOPs** of AI performance, making them ideal for high-performance AI workloads in desktop and edge computing environments.

![](https://img.shields.io/badge/OS-Windows-orange) ![](https://img.shields.io/badge/Quark_Quantizer-latest-blue) ![](https://img.shields.io/badge/Vitis_AI_EP-latest-blue) ![](https://img.shields.io/badge/DirectML_EP-latest-blue) ![](https://img.shields.io/badge/Python->3.6-green)
  * [ZenDNN: Accelerated Inference Library Optimized for AMD “Zen” CPUs](https://www.amd.com/zh-tw/developer/zendnn.html)
  * [Ryzen AI Software: GPU and NPU Support](https://ryzenai.docs.amd.com/en/latest/index.html)
  * [AMD Quark Quantizer: Efficient AI Model Deployment](https://www.amd.com/en/developer/resources/technical-articles/amd-quark-quantizer-for-efficient-ai-model-deployment.html)

</details>

<details>
<summary>NVIDIA Jetson GPU Module</summary>
  
Jetson Orin is a cutting-edge SoC designed for edge AI applications, featuring an **Arm CPU** and the powerful **Ampere architecture GPU**, delivering exceptional AI performance ranging from **67~275 TOPS**. Its GPU is optimized for high-performance parallel computing, making it ideal for deep learning inference, computer vision, and other AI workloads requiring high throughput.

![](https://img.shields.io/badge/OS-Ubuntu_|_JetPack-orange) ![](https://img.shields.io/badge/TensorRT-latest-blue) ![](https://img.shields.io/badge/Python->3.6-green)

</details>

<details>
<summary>WiseEye2 AI Processor</summary>

The WiseEye2 AI Processor is a low-power AI solution designed for always-on applications such as vision and audio recognition. It integrates **Arm Cortex-M** cores and a dedicated **Arm Ethos-U NPU**, delivering efficient AI inference for edge devices. Its compact design and low power consumption make it suitable for battery-powered devices.

![](https://img.shields.io/badge/OS-FreeRTOS_|_RT-Thread-orange) ![](https://img.shields.io/badge/Framework-TensorFlow_Lite_Micro-blue) ![](https://img.shields.io/badge/Language-C_|_C++-green)

  * [Deploy AI Models with TensorFlow Lite Micro](https://www.tensorflow.org/lite/microcontrollers)  
  * [Efficient AI on Arm Ethos-U NPUs](https://developer.arm.com/ip-products/processors/machine-learning/ethos-u)
  
</details>

<details>
<summary>Hailo AI Processor</summary>


The Hailo AI Processor is a high-performance AI solution designed for accelerating computer vision tasks. It features **26~40 TOPs** of AI performance and supports **mPCIe/M.2 interfaces**, enabling seamless integration with other modules. Its efficient architecture makes it ideal for edge AI applications requiring real-time processing and high throughput. **(*registration is required to access the documents)**

![](https://img.shields.io/badge/Data_Compiler-3.27.0-blue) ![](https://img.shields.io/badge/PyHailoRT-4.17-blue) ![](https://img.shields.io/badge/Python-3.8-green)
  * [Install Dataflow Compiler with Evaluation Board](https://hailo.ai/developer-zone/documentation/dataflow-compiler-v3-27-0/?sp_referrer=install/install.html)
  * [Install HailoRT (PCIe Driver) and pyHailoRT with mPCIe or M.2 board](https://hailo.ai/developer-zone/documentation/hailort-v4-17-0/?sp_referrer=install/install.html#ubuntu-installer-requirements)

</details>


<table>
    <tr>
        <th colspan=2>Platform</th>
        <th rowspan=2>MediaTek Genio<br>
        <th rowspan=2>AMD Ryzen/Radeon<br>
        <th rowspan=2>Microsoft Azure</th>
    </tr>
    <tr>
        <th>Category</th>
        <th>Platform</th>
    </tr>
    <tr>
        <td rowspan=1>Framework</td>
        <td>Multi-modal Q&A</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
    </tr>
    <tr>
        <td rowspan=3>Tools</td>
        <td>SQL-RAG</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Graph-RAG</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Baseline-RAG</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td rowspan=3>Functions</td>
        <td>OCR</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Stereo-Tracking</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Object-Detection</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
</table>







<table>
    <tr>
        <th>Category</th>
        <th>Application</th>
        <th>Pi<br>
        <th>Genio<br>
        <th>Ryzen</th>
        <th>Jetson</th>
        <th>WE</th>
        <th>Hailo</th>
    </tr>
    <tr>
        <td rowspan=3>CV</td>
        <td>Image Classification</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Object Detection</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td>Semantic Segmentation</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
    </tr>
    <tr>
        <td rowspan=1>NLP</td>
        <td>Text to Text</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
    </tr>
    <tr>
        <td rowspan=1>Voice Signals</td>
        <td>Speech-Recognition</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
    </tr>
    <tr>
        <td rowspan=2>Multi Modal</td>
        <td>Text to Image</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
    </tr>
    <tr>
        <td>Text to Voice</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:white_check_mark:</td>
        <td>:black_square_button:</td>
        <td>:black_square_button:</td>
    </tr>
</table>

## <div align="center">News</div>

* 2025/01 Added support for **ARM** as a deployment platform.
* 2024/12 Added support for **AMD** as a deployment platform.
* 2024/09 Released a [**Developer's Zone**](https://r300-ai.github.io/ITRI-AI-Hub/) for chipset tutorials.
* 2024/07 Started testing model deployment with **Hailo**.
* 2024/05 Released the [**AI Hub Portal**](https://e-aihub.dev/) as an application gallery.
* 2024/03 Established a partnership with **Microsoft Azure**.
* 2023/12 Initiated the project with **MediaTek** as an AI-on-Chip testing platform.

## <div align="center">Contridutors</div>

<a href="https://www.moea.gov.tw/Mns/populace/home/Home.aspx" target="AI晶片異質整合模組前瞻製造平台計畫"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/moea_logo.png" alt="MOEA logo" height="38" width="216"></a>&nbsp;
<a href="https://www.itri.org.tw/index.aspx" target="工業技術研究院"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/itri_EL_A.jpg" alt="ITRI logo" height="39"></a>&nbsp;
<a href="https://www.amd.com/zh-tw.html" target="amd"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/amd_logo.png" alt="amd logo" height="33"></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.arm.com/zh-TW/" target="Arm"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/arm_logo.png" alt="Arm logo" height="33"></a>&nbsp;&nbsp;
<a href="https://www.microsoft.com/zh-tw" target="microsoft"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/microsoft_logo.png" alt="amd logo" height="33"></a>&nbsp;&nbsp;&nbsp;
<a href="https://www-stage.mediatek.com/zh-tw/" target="聯發科技"><img src="https://github.com/R300-AI/ITRI-AI-Hub/blob/main/docs/assets/images/logo/mediatek_logo.png" alt="MediaTek logo" height="35"></a>&nbsp;


## <div align="center">License</div>

