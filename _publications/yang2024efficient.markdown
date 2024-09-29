---
layout: publication
title: Protrain Efficient LLM Training Via Memory45;aware Techniques
authors: Yang Hanmei, Zhou Jin, Fu Yao, Wang Xiaoqun, Roane Ramine, Guan Hui, Liu Tongping
conference: "Arxiv"
year: 2024
bibkey: yang2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08334"}
tags: ['Ethics And Bias', 'Tools', 'Training Techniques']
---
It is extremely memory45;hungry to train Large Language Models (LLM). To solve this problem existing work exploits the combination of CPU and GPU for the training process such as ZeRO45;Offload. Such a technique largely democratizes billion45;scale model training making it possible to train with few consumer graphics cards. However based on our observation existing frameworks often provide coarse45;grained memory management and require experienced experts in configuration tuning leading to suboptimal hardware utilization and performance. This paper proposes ProTrain a novel training system that intelligently balances memory usage and performance by coordinating memory computation and IO. ProTrain achieves adaptive memory management through Chunk45;Based Model State Management and Block45;Wise Activation Management guided by a Memory45;Aware Runtime Profiler without user intervention. ProTrain does not change the training algorithm and thus does not compromise accuracy. Experiments show that ProTrain improves training throughput by 1.43× to 2.71× compared to the SOTA training systems.
