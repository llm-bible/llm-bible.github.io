---
layout: publication
title: 'Boosting The Generalization And Reasoning Of Vision Language Models With Curriculum Reinforcement Learning'
authors: Huilin Deng, Ding Zou, Rui Ma, Hongchen Luo, Yang Cao, Yu Kang
conference: "Arxiv"
year: 2025
bibkey: deng2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07065"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Scaling Laws', 'Multimodal Models']
---
While state-of-the-art vision-language models (VLMs) have demonstrated
remarkable capabilities in complex visual-text tasks, their success heavily
relies on massive model scaling, limiting their practical deployment.
Small-scale VLMs offer a more practical alternative but face significant
challenges when trained with traditional supervised fine-tuning (SFT),
particularly in two aspects: out-of-domain (OOD) generalization and reasoning
abilities, which significantly lags behind the contemporary Large language
models (LLMs). To address these challenges, we propose Curriculum Reinforcement
Finetuning (Curr-ReFT), a novel post-training paradigm specifically designed
for small-scale VLMs. Inspired by the success of reinforcement learning in
LLMs, Curr-ReFT comprises two sequential stages: (1) Curriculum Reinforcement
Learning, which ensures steady progression of model capabilities through
difficulty-aware reward design, transitioning from basic visual perception to
complex reasoning tasks; and (2) Rejected Sampling-based Self-improvement,
which maintains the fundamental capabilities of VLMs through selective learning
from high-quality multimodal and language examples. Extensive experiments
demonstrate that models trained with Curr-ReFT paradigm achieve
state-of-the-art performance across various visual tasks in both in-domain and
out-of-domain settings. Moreover, our Curr-ReFT enhanced 3B model matches the
performance of 32B-parameter models, demonstrating that efficient training
paradigms can effectively bridge the gap between small and large models.
