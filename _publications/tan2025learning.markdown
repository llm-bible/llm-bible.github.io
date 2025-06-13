---
layout: publication
title: 'Remedy: Learning Machine Translation Evaluation From Human Preferences With Reward Modeling'
authors: Shaomu Tan, Christof Monz
conference: "Arxiv"
year: 2025
bibkey: tan2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13630'}
tags: ['WMT', 'GPT', 'Model Architecture', 'Tools', 'Prompting', 'Applications', 'Reinforcement Learning']
---
A key challenge in MT evaluation is the inherent noise and inconsistency of
human ratings. Regression-based neural metrics struggle with this noise, while
prompting LLMs shows promise at system-level evaluation but performs poorly at
segment level. In this work, we propose ReMedy, a novel MT metric framework
that reformulates translation evaluation as a reward modeling task. Instead of
regressing on imperfect human ratings directly, ReMedy learns relative
translation quality using pairwise preference data, resulting in a more
reliable evaluation. In extensive experiments across WMT22-24 shared tasks (39
language pairs, 111 MT systems), ReMedy achieves state-of-the-art performance
at both segment- and system-level evaluation. Specifically, ReMedy-9B surpasses
larger WMT winners and massive closed LLMs such as MetricX-13B,
XCOMET-Ensemble, GEMBA-GPT-4, PaLM-540B, and finetuned PaLM2. Further analyses
demonstrate that ReMedy delivers superior capability in detecting translation
errors and evaluating low-quality translations.
