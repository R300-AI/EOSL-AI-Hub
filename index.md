---
layout: default
title: Quick Start
nav_order: 1
---

# Welcome to ITRI AI Hub Tutorials
##### update : 2025/01 by ITRI (EOSL-R3)

<br>ITRI AI Hub provides simple, fast, and commercialized Edge AI implementation solutions for enterprises and developers. Before selecting a system, we recommend evaluating which devices are best suited for your applications based on factors such as model type, computing power, memory, and energy efficiency. The diagram below summarizes the memory and computing power distribution of the devices we have selected, helping you intuitively compare them with a variety of Model Zoo options, open-source community models, or other custom models.

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
AI on Chips enables various types of electronic devices to efficiently execute AI models, offering unparalleled opportunities to realize the vision of AI Everywhere. To achieve this, integrating CPUs, GPUs, and NPUs into Chiplets plays a critical role, overcoming traditional performance and power consumption bottlenecks. For vendor-specific solutions and Taiwan's self-developed Silicon IP, ITRI provides a pilot production line for heterogeneous integration with small-volume, diverse packaging. This process fully covers the design, manufacturing, verification, and system integration testing of Chiplets, helping enterprises and academia quickly enter the market and build innovative applications on top of it.
</div><br>


<strong>How to Get Started with Chiplets?</strong>
<div style="margin-left: 20px;">
To ensure that models can run efficiently on embedded systems, AI developers must identify the hardware specifications and architecture of the chips. This is essential to fully leverage the application performance of advanced AI chips. You can find more information on other pages of this document:
<ul>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/">Raspberry Pi Board</li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/genio-evk.html">Genio Board</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/docs/ryzen.html">Ryzen AI Board</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/">Jetson Board</a></li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/">WiseEye Visual AI Accelerator (MCU)</li>
    <li><a href="https://r300-ai.github.io/ITRI-AI-Hub/">Hailo Visual AI Accelerator (MCU)</a></li>
</ul>

在AI Hub，我們提供以上類型的Chiplet入門指南，包括系統配置方法和模型部署教程。 首先，您需先通過Retailer或Agent取得Evaluation Kit，然後依照官方文件的指示及需求配置工作環境及系統，除此之外，這個Developer Zone。

</div>

## **開源社群精選資源**
### Data Preparation
* [Label Studio: Open Source Data Labeling](https://labelstud.io/)
* [Albumentations: fast and flexible image augmentations](https://albumentations.ai/)

### Training Model

### Quantization and Deployment
* [Computer Vision Deployment on Genio DLAs Using Ultralytics Pre-Trained YOLOs]()