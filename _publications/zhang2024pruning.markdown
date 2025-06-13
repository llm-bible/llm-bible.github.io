---
layout: publication
title: 'Pruning As A Domain-specific LLM Extractor'
authors: Nan Zhang, Yanchi Liu, Xujiang Zhao, Wei Cheng, Runxue Bao, Rui Zhang, Prasenjit Mitra, Haifeng Chen
conference: "Arxiv"
year: 2024
bibkey: zhang2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06275"}
  - {name: "Code", url: "https://github.com/psunlpgroup/D-Pruner"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Has Code', 'Pruning']
---
Large Language Models (LLMs) have exhibited remarkable proficiency across a
wide array of NLP tasks. However, the escalation in model size also engenders
substantial deployment costs. While few efforts have explored model pruning
techniques to reduce the size of LLMs, they mainly center on general or
task-specific weights. This leads to suboptimal performance due to lacking
specificity on the target domain or generality on different tasks when applied
to domain-specific challenges. This work introduces an innovative unstructured
dual-pruning methodology, D-Pruner, for domain-specific compression on LLM. It
extracts a compressed, domain-specific, and task-agnostic LLM by identifying
LLM weights that are pivotal for general capabilities, like linguistic
capability and multi-task solving, and domain-specific knowledge. More
specifically, we first assess general weight importance by quantifying the
error incurred upon their removal with the help of an open-domain calibration
dataset. Then, we utilize this general weight importance to refine the training
loss, so that it preserves generality when fitting into a specific domain.
Moreover, by efficiently approximating weight importance with the refined
training loss on a domain-specific calibration dataset, we obtain a pruned
model emphasizing generality and specificity. Our comprehensive experiments
across various tasks in healthcare and legal domains show the effectiveness of
D-Pruner in domain-specific compression. Our code is available at
https://github.com/psunlpgroup/D-Pruner.
