---
layout: publication
title: NutePrune Efficient Progressive Pruning with Numerous Teachers for Large Language Models
authors: Li Shengrui, Chen Junzhe, Han Xueting, Bai Jing
conference: "Arxiv"
year: 2024
bibkey: li2024nuteprune
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09773"}
  - {name: "Code", url: "https://github.com/Lucius-lsr/NutePrune"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pruning', 'RAG', 'Reinforcement Learning']
---
The considerable size of Large Language Models (LLMs) presents notable deployment challenges particularly on resource-constrained hardware. Structured pruning offers an effective means to compress LLMs thereby reducing storage costs and enhancing inference speed for more efficient utilization. In this work we study data-efficient and resource-efficient structure pruning methods to obtain smaller yet still powerful models. Knowledge Distillation is well-suited for pruning as the intact model can serve as an excellent teacher for pruned students. However it becomes challenging in the context of LLMs due to memory constraints. To address this we propose an efficient progressive Numerous-teacher pruning method (NutePrune). NutePrune mitigates excessive memory costs by loading only one intact model and integrating it with various masks and LoRA modules enabling it to seamlessly switch between teacher and student roles. This approach allows us to leverage numerous teachers with varying capacities to progressively guide the pruned model enhancing overall performance. Extensive experiments across various tasks demonstrate the effectiveness of NutePrune. In LLaMA-7B zero-shot experiments NutePrune retains 97.17 of the performance of the original model at 20 sparsity and 95.07 at 25 sparsity. Our code is available at https://github.com/Lucius-lsr/NutePrune.
