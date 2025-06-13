---
layout: publication
title: 'Fast And Slow Generating: An Empirical Study On Large And Small Language Models Collaborative Decoding'
authors: Kaiyan Zhang, Jianyu Wang, Ning Ding, Biqing Qi, Ermo Hua, Xingtai Lv, Bowen Zhou
conference: "Arxiv"
year: 2024
bibkey: zhang2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12295"}
  - {name: "Code", url: "https://github.com/TsinghuaC3I/FS-GEN"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Large Language Models (LLMs) exhibit impressive capabilities across various
applications but encounter substantial challenges such as high inference
latency, considerable training costs, and the generation of hallucinations.
Collaborative decoding between large and small language models (SLMs) presents
a promising strategy to mitigate these issues through methods including
speculative decoding, contrastive decoding, and emulator or proxy fine-tuning.
However, the specifics of such collaborations, particularly from a unified
perspective, remain largely unexplored. Inspired by dual-process cognitive
theory, we propose a unified framework in this paper, termed Fast and Slow
Generating (FS-GEN). Within this framework, LLMs (sometimes along with SLMs)
are categorized as System 2 (slow and deliberate), while independent SLMs are
designated as System 1 (fast and intuitive). We provide a comprehensive
analysis of these collaborative methodologies, elucidating their common
properties and shedding light on the differential knowledge capabilities of
System 2 versus System 1 through the FS-GEN framework. Our findings indicate
that only a small proportion of collaborative interactions (approximately less
than 20% in most instances) are necessary across various methods. These
interactions between System 1 and System 2 conform to a scaling law related to
the parameter ratios, enabling predictable collaboration. Furthermore, we
explore the specific conditions under which collaboration proves most
effective, particularly from an uncertainty perspective, offering novel
insights that may guide future optimization efforts. Our research underscores
that the fundamental distinction between System 1 and System 2 lies in the
uncertainty of next token predictions, where interventions by System 2 are
crucial to support System 1. Code for Reproduction:
https://github.com/TsinghuaC3I/FS-GEN
