---
layout: publication
title: 'Leveraging Open Knowledge For Advancing Task Expertise In Large Language Models'
authors: Yuncheng Yang, Yulei Qin, Tong Wu, Zihan Xu, Gang Li, Pengcheng Guo, Hang Shao, Yuchen Shi, Ke Li, Xing Sun, Jie Yang, Yun Gu
conference: "Arxiv"
year: 2024
bibkey: yang2024leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.15915'}
  - {name: "Code", url: 'https://github.com/Yaphabates/Rocket'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
The cultivation of expertise for large language models (LLMs) to solve tasks
of specific areas often requires special-purpose tuning with calibrated
behaviors on the expected stable outputs. To avoid huge cost brought by manual
preparation of instruction datasets and training resources up to hundreds of
hours, the exploitation of open knowledge including a wealth of low rank
adaptation (LoRA) models and instruction datasets serves as a good starting
point. However, existing methods on model and data selection focus on the
performance of general-purpose capabilities while neglecting the knowledge gap
exposed in domain-specific deployment. In the present study, we propose to
bridge such gap by introducing few human-annotated samples (i.e., K-shot) for
advancing task expertise of LLMs with open knowledge. Specifically, we develop
an efficient and scalable pipeline to cost-efficiently produce task experts
where K-shot data intervene in selecting the most promising expert candidates
and the task-relevant instructions. A mixture-of-expert (MoE) system is built
to make the best use of individual-yet-complementary knowledge between multiple
experts. We unveil the two keys to the success of a MoE system, 1) the abidance
by K-shot, and 2) the insistence on diversity. For the former, we ensure that
models that truly possess problem-solving abilities on K-shot are selected
rather than those blind guessers. Besides, during data selection, instructions
that share task-relevant contexts with K-shot are prioritized. For the latter,
we highlight the diversity of constituting experts and that of the fine-tuning
instructions throughout the model and data selection process. Extensive
experimental results confirm the superiority of our approach over existing
methods on utilization of open knowledge across various tasks. Our codes will
be available at https://github.com/Yaphabates/Rocket.
