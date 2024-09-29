---
layout: publication
title: ASPEN High45;throughput Lora Fine45;tuning Of Large Language Models With A Single GPU
authors: Ye Zhengmao, Li Dengchun, Tian Jingqi, Lan Tingfeng, Zuo Jie, Duan Lei, Lu Hui, Jiang Yexi, Sha Jian, Zhang Ke, Tang Mingjie
conference: "Arxiv"
year: 2023
bibkey: ye2023high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02515"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer45;based large language models (LLMs) have demonstrated outstanding performance across diverse domains particularly when fine45;turned for specific domains. Recent studies suggest that the resources required for fine45;tuning LLMs can be economized through parameter45;efficient methods such as Low45;Rank Adaptation (LoRA). While LoRA effectively reduces computational burdens and resource demands it currently supports only a single45;job fine45;tuning setup. In this paper we present ASPEN a high45;throughput framework for fine45;tuning LLMs. ASPEN efficiently trains multiple jobs on a single GPU using the LoRA method leveraging shared pre45;trained model and adaptive scheduling. ASPEN is compatible with transformer45;based language models like LLaMA and ChatGLM etc. Experiments show that ASPEN saves 5337; of GPU memory when training multiple LLaMA45;7B models on NVIDIA A100 80GB GPU and boosts training throughput by about 1737; compared to existing methods when training with various pre45;trained models on different GPUs. The adaptive scheduling algorithm reduces turnaround time by 2437; end45;to45;end training latency by 1237; prioritizing jobs and preventing out45;of45;memory issues.
