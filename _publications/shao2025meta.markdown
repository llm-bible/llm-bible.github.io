---
layout: publication
title: 'In-context Meta Lora Generation'
authors: Yihua Shao, Minxi Yan, Yang Liu, Siyu Chen, Wenjie Chen, Xinwei Long, Ziyang Yan, Lei Li, Chenyu Zhang, Nicu Sebe, Hao Tang, Yan Wang, Hao Zhao, Mengzhu Wang, Jingcai Guo
conference: "Arxiv"
year: 2025
bibkey: shao2025meta
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.17635'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Low-rank Adaptation (LoRA) has demonstrated remarkable capabilities for task
specific fine-tuning. However, in scenarios that involve multiple tasks,
training a separate LoRA model for each one results in considerable
inefficiency in terms of storage and inference. Moreover, existing parameter
generation methods fail to capture the correlations among these tasks, making
multi-task LoRA parameter generation challenging. To address these limitations,
we propose In-Context Meta LoRA (ICM-LoRA), a novel approach that efficiently
achieves task-specific customization of large language models (LLMs).
Specifically, we use training data from all tasks to train a tailored
generator, Conditional Variational Autoencoder (CVAE). CVAE takes task
descriptions as inputs and produces task-aware LoRA weights as outputs. These
LoRA weights are then merged with LLMs to create task-specialized models
without the need for additional fine-tuning. Furthermore, we utilize in-context
meta-learning for knowledge enhancement and task mapping, to capture the
relationship between tasks and parameter distributions. As a result, our method
achieves more accurate LoRA parameter generation for diverse tasks using CVAE.
ICM-LoRA enables more accurate LoRA parameter reconstruction than current
parameter reconstruction methods and is useful for implementing task-specific
enhancements of LoRA parameters. At the same time, our method occupies 283MB,
only 1% storage compared with the original LoRA.
