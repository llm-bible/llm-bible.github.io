---
layout: publication
title: 'ASPEN: High-throughput Lora Fine-tuning Of Large Language Models With A Single GPU'
authors: Ye Zhengmao, Li Dengchun, Tian Jingqi, Lan Tingfeng, Zuo Jie, Duan Lei, Lu Hui, Jiang Yexi, Sha Jian, Zhang Ke, Tang Mingjie
conference: "Arxiv"
year: 2023
bibkey: ye2023high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02515"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer-based large language models (LLMs) have demonstrated outstanding performance across diverse domains, particularly when fine-turned for specific domains. Recent studies suggest that the resources required for fine-tuning LLMs can be economized through parameter-efficient methods such as Low-Rank Adaptation (LoRA). While LoRA effectively reduces computational burdens and resource demands, it currently supports only a single-job fine-tuning setup. In this paper, we present ASPEN, a high-throughput framework for fine-tuning LLMs. ASPEN efficiently trains multiple jobs on a single GPU using the LoRA method, leveraging shared pre-trained model and adaptive scheduling. ASPEN is compatible with transformer-based language models like LLaMA and ChatGLM, etc. Experiments show that ASPEN saves 53&#37; of GPU memory when training multiple LLaMA-7B models on NVIDIA A100 80GB GPU and boosts training throughput by about 17&#37; compared to existing methods when training with various pre-trained models on different GPUs. The adaptive scheduling algorithm reduces turnaround time by 24&#37;, end-to-end training latency by 12&#37;, prioritizing jobs and preventing out-of-memory issues.
