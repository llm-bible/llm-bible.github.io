---
layout: publication
title: 'From Text To Space: Mapping Abstract Spatial Models In Llms During A Grid-world Navigation Task'
authors: Nicolas Martorell
conference: "Arxiv"
year: 2025
bibkey: martorell2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16690"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Understanding how large language models (LLMs) represent and reason about
spatial information is crucial for building robust agentic systems that can
navigate real and simulated environments. In this work, we investigate the
influence of different text-based spatial representations on LLM performance
and internal activations in a grid-world navigation task. By evaluating models
of various sizes on a task that requires navigating toward a goal, we examine
how the format used to encode spatial information impacts decision-making. Our
experiments reveal that cartesian representations of space consistently yield
higher success rates and path efficiency, with performance scaling markedly
with model size. Moreover, probing LLaMA-3.1-8B revealed subsets of internal
units, primarily located in intermediate layers, that robustly correlate with
spatial features, such as the position of the agent in the grid or action
correctness, regardless of how that information is represented, and are also
activated by unrelated spatial reasoning tasks. This work advances our
understanding of how LLMs process spatial information and provides valuable
insights for developing more interpretable and robust agentic AI systems.
