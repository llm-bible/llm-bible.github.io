---
layout: publication
title: 'Mode: Effective Multi-task Parameter Efficient Fine-tuning With A Mixture Of Dyadic Experts'
authors: Lin Ning, Harsh Lara, Meiqi Guo, Abhinav Rastogi
conference: "Arxiv"
year: 2024
bibkey: ning2024effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01505"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning']
---
Parameter-efficient fine-tuning techniques like Low-Rank Adaptation (LoRA)
have revolutionized the adaptation of large language models (LLMs) to diverse
tasks. Recent efforts have explored mixtures of LoRA modules for multi-task
settings. However, our analysis reveals redundancy in the down-projection
matrices of these architectures. This observation motivates our proposed
method, Mixture of Dyadic Experts (MoDE), which introduces a novel design for
efficient multi-task adaptation. This is done by sharing the down-projection
matrix across tasks and employing atomic rank-one adapters, coupled with
routers that allow more sophisticated task-level specialization. Our design
allows for more fine-grained mixing, thereby increasing the model's ability to
jointly handle multiple tasks. We evaluate MoDE on the Supernatural
Instructions (SNI) benchmark consisting of a diverse set of 700+ tasks and
demonstrate that it outperforms state-of-the-art multi-task parameter-efficient
fine-tuning (PEFT) methods, without introducing additional parameters. Our
findings contribute to a deeper understanding of parameter efficiency in
multi-task LLM adaptation and provide a practical solution for deploying
high-performing, lightweight models.
