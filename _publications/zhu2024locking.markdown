---
layout: publication
title: 'Locking Down The Finetuned Llms Safety'
authors: Minjun Zhu, Linyi Yang, Yifan Wei, Ningyu Zhang, Yue Zhang
conference: "Arxiv"
year: 2024
bibkey: zhu2024locking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10343"}
  - {name: "Code", url: "https://github.com/zhu-minjun/SafetyLock"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Fine-tuning large language models (LLMs) on additional datasets is often
necessary to optimize them for specific downstream tasks. However, existing
safety alignment measures, which restrict harmful behavior during inference,
are insufficient to mitigate safety risks during fine-tuning. Alarmingly,
fine-tuning with just 10 toxic sentences can make models comply with harmful
instructions. We introduce SafetyLock, a novel alignment intervention method
that maintains robust safety post-fine-tuning through efficient and
transferable mechanisms. SafetyLock leverages our discovery that fine-tuned
models retain similar safety-related activation representations to their base
models. This insight enables us to extract what we term the Meta-SafetyLock, a
set of safety bias directions representing key activation patterns associated
with safe responses in the original model. We can then apply these directions
universally to fine-tuned models to enhance their safety. By searching for
activation directions across multiple token dimensions, SafetyLock achieves
enhanced robustness and transferability. SafetyLock re-aligns fine-tuned models
in under 0.01 seconds without additional computational cost. Our experiments
demonstrate that SafetyLock can reduce the harmful instruction response rate
from 60% to below 1% in toxic fine-tuned models. It surpasses traditional
methods in both performance and efficiency, offering a scalable, non-invasive
solution for ensuring the safety of customized LLMs. Our analysis across
various fine-tuning scenarios confirms SafetyLock's robustness, advocating its
integration into safety protocols for aligned LLMs. The code is released at
https://github.com/zhu-minjun/SafetyLock.
