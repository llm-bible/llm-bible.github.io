---
layout: publication
title: 'Efficiency In Focus: Layernorm As A Catalyst For Fine-tuning Medical Visual Language Pre-trained Models'
authors: Jiawei Chen, Dingkang Yang, Yue Jiang, Mingcheng Li, Jinjie Wei, Xiaolu Hou, Lihua Zhang
conference: "Arxiv"
year: 2024
bibkey: chen2024efficiency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16385"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
In the realm of Medical Visual Language Models (Med-VLMs), the quest for
universal efficient fine-tuning mechanisms remains paramount, especially given
researchers in interdisciplinary fields are often extremely short of training
resources, yet largely unexplored. Given the unique challenges in the medical
domain, such as limited data scope and significant domain-specific
requirements, evaluating and adapting Parameter-Efficient Fine-Tuning (PEFT)
methods specifically for Med-VLMs is essential. Most of the current PEFT
methods on Med-VLMs have yet to be comprehensively investigated but mainly
focus on adding some components to the model's structure or input. However,
fine-tuning intrinsic model components often yields better generality and
consistency, and its impact on the ultimate performance of Med-VLMs has been
widely overlooked and remains understudied. In this paper, we endeavour to
explore an alternative to traditional PEFT methods, especially the impact of
fine-tuning LayerNorm layers, FFNs and Attention layers on the Med-VLMs. Our
comprehensive studies span both small-scale and large-scale Med-VLMs,
evaluating their performance under various fine-tuning paradigms across tasks
such as Medical Visual Question Answering and Medical Imaging Report
Generation. The findings reveal unique insights into the effects of intrinsic
parameter fine-tuning methods on fine-tuning Med-VLMs to downstream tasks and
expose fine-tuning solely the LayerNorm layers not only surpasses the
efficiency of traditional PEFT methods but also retains the model's accuracy
and generalization capabilities across a spectrum of medical downstream tasks.
The experiments show LayerNorm fine-tuning's superior adaptability and
scalability, particularly in the context of large-scale Med-VLMs.
