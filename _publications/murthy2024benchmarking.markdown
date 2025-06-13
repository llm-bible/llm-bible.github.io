---
layout: publication
title: 'Mobileaibench: Benchmarking Llms And Lmms For On-device Use Cases'
authors: Rithesh Murthy, Liangwei Yang, Juntao Tan, Tulika Manoj Awalgaonkar, Yilun Zhou, Shelby Heinecke, Sachin Desai, Jason Wu, Ran Xu, Sarah Tan, Jianguo Zhang, Zhiwei Liu, Shirley Kokane, Zuxin Liu, Ming Zhu, Huan Wang, Caiming Xiong, Silvio Savarese
conference: "Arxiv"
year: 2024
bibkey: murthy2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10290"}
tags: ['Responsible AI', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models', 'Quantization']
---
The deployment of Large Language Models (LLMs) and Large Multimodal Models
(LMMs) on mobile devices has gained significant attention due to the benefits
of enhanced privacy, stability, and personalization. However, the hardware
constraints of mobile devices necessitate the use of models with fewer
parameters and model compression techniques like quantization. Currently, there
is limited understanding of quantization's impact on various task performances,
including LLM tasks, LMM tasks, and, critically, trust and safety. There is a
lack of adequate tools for systematically testing these models on mobile
devices. To address these gaps, we introduce MobileAIBench, a comprehensive
benchmarking framework for evaluating mobile-optimized LLMs and LMMs.
MobileAIBench assesses models across different sizes, quantization levels, and
tasks, measuring latency and resource consumption on real devices. Our two-part
open-source framework includes a library for running evaluations on desktops
and an iOS app for on-device latency and hardware utilization measurements. Our
thorough analysis aims to accelerate mobile AI research and deployment by
providing insights into the performance and feasibility of deploying LLMs and
LMMs on mobile platforms.
