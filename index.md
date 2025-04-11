---
layout: default
title: Quick Start
nav_order: 1
---

# Welcome to ITRI AI Hub Tutorials
##### update : 2025/01 by ITRI (EOSL-R3)

<br>ITRI AI Hub offers simple, fast, and commercialized Edge AI implementation solutions for enterprises and developers. Before selecting a system, we recommend evaluating which devices are suitable for your applications based on model type, computing power, memory, and energy efficiency. The diagram below summarizes the memory and computing power distribution of devices we selected, helping you compare them more intuitively with <a href="https://github.com/R300-AI/ITRI-AI-Hub/tree/main/Model-Zoo">Model Zoo</a>, open-source communities, or other custom models.

<div align="center">
<img src="docs/assets/images/pages/metric_of_all_devices.png" width="760"/>
</div>

## **Development Flow Overview**

<div style="margin-left: 20px;">
<p>To support various types of AI tasks, users can pre-select base models from GitHub projects, open-source frameworks, or train their desired models using PyTorch or TensorFlow. These models rely on self-built workstations, servers, or cloud-hosted data centers during the design and development phases. 

In this regard, ITRI provides online resources such as <a href="https://azure.microsoft.com/en-us/products/machine-learning">Azure AI Foundry</a> and <a href="https://www.aita.org.tw/News/news_more?id=82a8da71e7cc4cf6acb657a789165822">AMD Instinct Cluster</a> to help you easily adapt and develop your products without incurring significant infrastructure maintenance costs. Additionally, you can quickly deploy your innovative applications by integrating pre-built tools and frameworks from the open-source community (e.g., YOLO, LLaMA, Whisper...) to obtain models.</p>
</div>

<strong>AI on Chips: Enabling the Future of AI Everywhere</strong>
<div style="margin-left: 20px;">
AI on Chips enables various types of electronic devices to efficiently execute AI models, offering unparalleled opportunities to realize the vision of AI Everywhere. To achieve this, Chiplets play a critical role by integrating CPUs, GPUs, and NPUs into a single chip, overcoming traditional performance and power consumption bottlenecks. For vendor-specific solutions and Taiwan's self-developed Silicon IP, ITRI provides a pilot production line for heterogeneous integration with small-volume, diverse packaging. This process fully covers the design, manufacturing, verification, and system integration testing of Chiplets, helping enterprises and academia quickly enter the market and achieve innovative applications.
</div>


<strong>如何開始使用小晶片?</strong>
<div style="margin-left: 20px;">
To ensure that the model can execute efficiently on embedded systems,
<ul></ul>
</div>

<strong>Step3. Inference</strong>
<div style="margin-left: 20px;">
Follow the instructions to configure the engine and operating environment for your specified chips. This will allow you to deploy binary files and perform computations on the system.
<ul>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/genio-evk.html">Genio Evaluation Kits</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/hailo.html">Hailo AI Accelerator</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/ryzen.html">Ryzen AI Processor</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/jetson-evk.html">Jetson Evaluation Kits</a></li>
</ul>
</div>
</div>

Here, the ITRI AI Hub plays a crucial role by offering comprehensive development resources and tutorials for each stage of the process. This support enables enterprises and individual users to efficiently and quickly validate their new AI applications. For more information, please visit the "Developer Support" section.

</div>

## **How to Build Your Own Application?**
### Data Preparation
* [Label Studio: Open Source Data Labeling](https://labelstud.io/)
* [Albumentations: fast and flexible image augmentations](https://albumentations.ai/)

### Training Model

### Quantization and Deployment
* [Computer Vision Deployment on Genio DLAs Using Ultralytics Pre-Trained YOLOs]()