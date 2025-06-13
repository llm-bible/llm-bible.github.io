---
layout: publication
title: 'QCRD: Quality-guided Contrastive Rationale Distillation For Large Language Models'
authors: Wei Wang, Zhaowei Li, Qi Xu, Yiqing Cai, Hang Song, Qi Qi, Ran Zhou, Zhida Huang, Tao Wang, Li Xiao
conference: "Arxiv"
year: 2024
bibkey: wang2024quality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13014"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Distillation']
---
The deployment of large language models (LLMs) faces considerable challenges
concerning resource constraints and inference efficiency. Recent research has
increasingly focused on smaller, task-specific models enhanced by distilling
knowledge from LLMs. However, prior studies have often overlooked the diversity
and quality of knowledge, especially the untapped potential of negative
knowledge. Constructing effective negative knowledge remains severely
understudied. In this paper, we introduce a novel framework called
quality-guided contrastive rationale distillation aimed at enhancing reasoning
capabilities through contrastive knowledge learning. For positive knowledge, we
enrich its diversity through temperature sampling and employ self-consistency
for further denoising and refinement. For negative knowledge, we propose an
innovative self-adversarial approach that generates low-quality rationales by
sampling previous iterations of smaller language models, embracing the idea
that one can learn from one's own weaknesses. A contrastive loss is developed
to distill both positive and negative knowledge into smaller language models,
where an online-updating discriminator is integrated to assess qualities of
rationales and assign them appropriate weights, optimizing the training
process. Through extensive experiments across multiple reasoning tasks, we
demonstrate that our method consistently outperforms existing distillation
techniques, yielding higher-quality rationales.
