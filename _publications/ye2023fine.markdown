---
layout: publication
title: 'Mlora: Fine-tuning Lora Adapters Via Highly-efficient Pipeline Parallelism In Multiple Gpus'
authors: Zhengmao Ye, Dengchun Li, Zetao Hu, Tingfeng Lan, Jian Sha, Sicong Zhang, Lei Duan, Jie Zuo, Hui Lu, Yuanchun Zhou, Mingjie Tang
conference: "Arxiv"
year: 2023
bibkey: ye2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02515"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Applications']
---
Transformer-based, pre-trained large language models (LLMs) have demonstrated
outstanding performance across diverse domains, particularly in the emerging
\{\em pretrain-then-finetune\} paradigm. Low-Rank Adaptation (LoRA), a
parameter-efficient fine-tuning method, is commonly used to adapt a base LLM to
multiple downstream tasks. Further, LLM platforms enable developers to
fine-tune multiple models and develop various domain-specific applications
simultaneously. However, existing model parallelism schemes suffer from high
communication overhead and inefficient GPU utilization when training multiple
LoRA tasks across GPUs and machines.
  In this paper, we present mLoRA, a parallelism-efficient fine-tuning system
designed for training multiple LoRA across GPUs and machines. mLoRA introduces
a novel LoRA-aware pipeline parallelism scheme that efficiently pipelines
independent LoRA adapters and their distinct fine-tuning stages across GPUs and
machines, along with a new LoRA-efficient operator to enhance GPU utilization
during pipelined LoRA training. Our extensive evaluation shows that mLoRA can
significantly reduce average fine-tuning task completion time, e.g., by 30%,
compared to state-of-the-art methods like FSDP. More importantly, mLoRA enables
simultaneous fine-tuning of larger models, e.g., two Llama-2-13B models on four
NVIDIA RTX A6000 48GB GPUs, which is not feasible for FSDP due to high memory
requirements. Hence, mLoRA not only increases fine-tuning efficiency but also
makes it more accessible on cost-effective GPUs. mLoRA has been deployed in
AntGroup's production environment.
