---
layout: publication
title: 'Beyond Pattern Recognition: Probing Mental Representations Of Lms'
authors: Moritz Miller, Kumar Shridhar
conference: "Arxiv"
year: 2025
bibkey: miller2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16717"}
tags: ['Interpretability and Explainability', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Language Models (LMs) have demonstrated impressive capabilities in solving
complex reasoning tasks, particularly when prompted to generate intermediate
explanations. However, it remains an open question whether these intermediate
reasoning traces represent a dynamic, evolving thought process or merely
reflect sophisticated pattern recognition acquired during large scale pre
training. Drawing inspiration from human cognition, where reasoning unfolds
incrementally as new information is assimilated and internal models are
continuously updated, we propose to delve deeper into the mental model of
various LMs. We propose a new way to assess the mental modeling of LMs, where
they are provided with problem details gradually, allowing each new piece of
data to build upon and refine the model's internal representation of the task.
We systematically compare this step by step mental modeling strategy with
traditional full prompt methods across both text only and vision and text
modalities. Experiments on the MathWorld dataset across different model sizes
and problem complexities confirm that both text-based LLMs and multimodal LMs
struggle to create mental representations, questioning how their internal
cognitive processes work.
