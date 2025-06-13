---
layout: publication
title: 'Orchestrate Multimodal Data With Batch Post-balancing To Accelerate Multimodal Large Language Model Training'
authors: Yijie Zheng, Bangjun Xiao, Lei Shi, Xiaoyang Li, Faming Wu, Tianyu Li, Xuefeng Xiao, Yang Zhang, Yuxuan Wang, Shouda Liu
conference: "Arxiv"
year: 2025
bibkey: zheng2025orchestrate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23830"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Tools', 'GPT', 'Fine-Tuning', 'Attention Mechanism']
---
Multimodal large language models (MLLMs), such as GPT-4o, are garnering
significant attention. During the exploration of MLLM training, we identified
Modality Composition Incoherence, a phenomenon that the proportion of a certain
modality varies dramatically across different examples. It exacerbates the
challenges of addressing mini-batch imbalances, which lead to uneven GPU
utilization between Data Parallel (DP) instances and severely degrades the
efficiency and scalability of MLLM training, ultimately affecting training
speed and hindering further research on MLLMs.
  To address these challenges, we introduce OrchMLLM, a comprehensive framework
designed to mitigate the inefficiencies in MLLM training caused by Modality
Composition Incoherence. First, we propose Batch Post-Balancing Dispatcher, a
technique that efficiently eliminates mini-batch imbalances in sequential data.
Additionally, we integrate MLLM Global Orchestrator into the training framework
to orchestrate multimodal data and tackle the issues arising from Modality
Composition Incoherence. We evaluate OrchMLLM across various MLLM sizes,
demonstrating its efficiency and scalability. Experimental results reveal that
OrchMLLM achieves a Model FLOPs Utilization (MFU) of \\(41.6%\\) when training an
84B MLLM with three modalities on \\(2560\\) H100 GPUs, outperforming Megatron-LM
by up to \\(3.1\times\\) in throughput.
