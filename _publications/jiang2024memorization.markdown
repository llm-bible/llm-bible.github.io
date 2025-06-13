---
layout: publication
title: 'Memorization Over Reasoning? Exposing And Mitigating Verbatim Memorization In Large Language Models'' Character Understanding Evaluation'
authors: Yuxuan Jiang, Francis Ferraro
conference: "Arxiv"
year: 2024
bibkey: jiang2024memorization
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.14368'}
tags: ['Reinforcement Learning', 'Pre-Training', 'Training Techniques']
---
Recently, Large Language Models (LLMs) have shown impressive performance in
character understanding tasks, such as analyzing the roles, personalities, and
relationships of fictional characters. However, the extensive pre-training
corpora used by LLMs raise concerns that they may rely on memorizing popular
fictional works rather than genuinely understanding and reasoning about them.
In this work, we argue that 'gist memory'-capturing essential meaning - should
be the primary mechanism for character understanding tasks, as opposed to
'verbatim memory' - exact match of a string. We introduce a simple yet
effective method to mitigate mechanized memorization in character understanding
evaluations while preserving the essential implicit cues needed for
comprehension and reasoning. Our approach reduces memorization-driven
performance on popular fictional works from 96% accuracy to 72% and results in
up to an 18% drop in accuracy across various character understanding tasks.
These findings underscore the issue of data contamination in existing
benchmarks, which often measure memorization rather than true character
understanding.
