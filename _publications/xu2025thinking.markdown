---
layout: publication
title: 'Twt: Thinking Without Tokens By Habitual Reasoning Distillation With Multi-teachers'' Guidance'
authors: Jingxian Xu, Mengyu Zhou, Weichang Liu, Hanbing Liu, Shi Han, Dongmei Zhang
conference: "Arxiv"
year: 2025
bibkey: xu2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.24198"}
tags: ['Efficiency and Optimization', 'Distillation']
---
Large Language Models (LLMs) have made significant strides in problem-solving
by incorporating reasoning processes. However, this enhanced reasoning
capability results in an increased number of output tokens during inference,
leading to higher computational costs. To address this challenge, we propose
TwT (Thinking without Tokens), a method that reduces inference-time costs
through habitual reasoning distillation with multi-teachers' guidance, while
maintaining high performance. Our approach introduces a Habitual Reasoning
Distillation method, which internalizes explicit reasoning into the model's
habitual behavior through a Teacher-Guided compression strategy inspired by
human cognition. Additionally, we propose Dual-Criteria Rejection Sampling
(DCRS), a technique that generates a high-quality and diverse distillation
dataset using multiple teacher models, making our method suitable for
unsupervised scenarios. Experimental results demonstrate that TwT effectively
reduces inference costs while preserving superior performance, achieving up to
a 13.6% improvement in accuracy with fewer output tokens compared to other
distillation methods, offering a highly practical solution for efficient LLM
deployment.
