---
layout: publication
title: Characterization of Large Language Model Development in the Datacenter
authors: Hu Qinghao, Ye Zhisheng, Wang Zerui, Wang Guoteng, Zhang Meng, Chen Qiaoling, Sun Peng, Lin Dahua, Wang Xiaolin, Luo Yingwei, Wen Yonggang, Zhang Tianwei
conference: "Arxiv"
year: 2024
bibkey: hu2024characterization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07648"}
tags: ['Efficiency And Optimization', 'Large Scale Training', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have presented impressive performance across several transformative tasks. However it is non-trivial to efficiently utilize large-scale cluster resources to develop LLMs often riddled with numerous challenges such as frequent hardware failures intricate parallelization strategies and imbalanced resource utilization. In this paper we present an in-depth characterization study of a six-month LLM development workload trace collected from our GPU datacenter Acme. Specifically we investigate discrepancies between LLMs and prior task-specific Deep Learning (DL) workloads explore resource utilization patterns and identify the impact of various job failures. Our analysis summarizes hurdles we encountered and uncovers potential opportunities to optimize systems tailored for LLMs. Furthermore we introduce our system efforts (1) fault-tolerant pretraining which enhances fault tolerance through LLM-involved failure diagnosis and automatic recovery. (2) decoupled scheduling for evaluation which achieves timely performance feedback via trial decomposition and scheduling optimization.
