---
layout: publication
title: 'Bidora: Bi-level Optimization-based Weight-decomposed Low-rank Adaptation'
authors: Peijia Qin, Ruiyi Zhang, Pengtao Xie
conference: "Arxiv"
year: 2024
bibkey: qin2024bi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09758"}
  - {name: "Code", url: "https://anonymous.4open.science/r/BiDoRA-5D31"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Parameter-efficient fine-tuning (PEFT) of large language models (LLMs) has
gained considerable attention as a flexible and efficient way of adapting LLMs
to downstream tasks. Among these methods, weighted decomposed low-rank
adaptation (DoRA) has emerged as a promising approach. DoRA bridges the gap
between low-rank adaptation (LoRA) and full fine-tuning (FT) by decomposing the
weight matrices into magnitude and direction components, thereby maintaining
learning behavior similar to FT. Although DoRA shows encouraging performance,
it introduces additional parameters compared to LoRA, which potentially
increases the risk of overfitting. Moreover, optimizing magnitude and direction
simultaneously leads to a coupled gradient updating pattern for both
components, limiting its learning capacity. To overcome these limitations, we
propose BiDoRA, a bi-level optimization-based PEFT method. In BiDoRA, the
direction and magnitude components are optimized on two distinct datasets at
different optimization levels, mitigating the risk of overfitting.
Additionally, the asynchronous optimization of the two components promotes
their decoupling, allowing for more flexible gradient updates suitable for
various downstream tasks. Evaluation of BiDoRA on fourteen datasets spanning
natural language understanding, natural language generation, and token
classification reveals that it significantly outperforms DoRA and other PEFT
methods. The superior performance of BiDoRA underscores its effectiveness. The
code for BiDoRA is available at https://anonymous.4open.science/r/BiDoRA-5D31.
