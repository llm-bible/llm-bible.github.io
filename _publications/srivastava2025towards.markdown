---
layout: publication
title: 'Towards Reasoning Ability Of Small Language Models'
authors: Gaurav Srivastava, Shuxiang Cao, Xuan Wang
conference: "Arxiv"
year: 2025
bibkey: srivastava2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11569"}
tags: ['Efficiency and Optimization', 'Survey Paper', 'Pruning', 'Security', 'Training Techniques', 'Quantization', 'Prompting', 'Distillation']
---
Reasoning has long been viewed as an emergent property of large language
models (LLMs), appearing at or above a certain scale (\\(\sim\\)100B parameters).
However, recent studies challenge this assumption, showing that small language
models (SLMs) can also achieve competitive reasoning performance. SLMs are
increasingly favored for their efficiency and deployability. However, there is
a lack of systematic study on the reasoning abilities of diverse SLMs,
including those trained from scratch or derived from LLMs through quantization,
pruning, and distillation. This raises a critical question: Can SLMs achieve
reasoning abilities comparable to LLMs? In this work, we systematically survey,
benchmark, and analyze 72 SLMs from six model families across 14 reasoning
benchmarks. For reliable evaluation, we examine four evaluation methods and
compare four LLM judges against human evaluations on 800 data points. We repeat
all experiments three times to ensure a robust performance assessment.
Additionally, we analyze the impact of different prompting strategies in small
models. Beyond accuracy, we also evaluate model robustness under adversarial
conditions and intermediate reasoning steps. Our findings challenge the
assumption that scaling is the only way to achieve strong reasoning. Instead,
we foresee a future where SLMs with strong reasoning capabilities can be
developed through structured training or post-training compression. They can
serve as efficient alternatives to LLMs for reasoning-intensive tasks.
