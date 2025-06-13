---
layout: publication
title: 'Sftmix: Elevating Language Model Instruction Tuning With Mixup Recipe'
authors: Yuxin Xiao, Shujian Zhang, Wenxuan Zhou, Marzyeh Ghassemi, Sanqiang Zhao
conference: "Arxiv"
year: 2024
bibkey: xiao2024elevating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05248"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
To acquire instruction-following capabilities, large language models (LLMs)
undergo instruction tuning, where they are trained on instruction-response
pairs using next-token prediction (NTP). Efforts to improve instruction tuning
often focus on higher-quality supervised fine-tuning (SFT) datasets, typically
requiring data filtering with proprietary LLMs or human annotation. In this
paper, we take a different approach by proposing SFTMix, a novel Mixup-based
recipe that elevates LLM instruction tuning beyond the conventional NTP
paradigm, without relying on well-curated datasets. Observing that LLMs exhibit
uneven confidence across the semantic representation space, we argue that
examples with different confidence levels should play distinct roles in
instruction tuning--confident data is prone to overfitting, while unconfident
data is harder to generalize. Based on this insight, SFTMix leverages training
dynamics to identify examples with varying confidence levels, interpolates them
to bridge the confidence gap, and applies a Mixup-based regularization to
support learning on these additional, interpolated examples. By propagating
supervision signals across confidence regions and encouraging linear behavior
between them, SFTMix mitigates overfitting in confident examples while
enhancing generalization in unconfident ones. We demonstrate the effectiveness
of SFTMix in both instruction-following and healthcare-specific SFT tasks, with
consistent improvements across LLM families and SFT datasets of varying sizes
and qualities. Extensive analyses across six directions highlight SFTMix's
compatibility with data selection, adaptability to compute-constrained
scenarios, and scalability to broader applications.
