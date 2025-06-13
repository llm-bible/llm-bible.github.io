---
layout: publication
title: 'Semantic Self-consistency: Enhancing Language Model Reasoning Via Semantic Weighting'
authors: Tim Knappe, Ryan Li, Ayush Chauhan, Kaylee Chhua, Kevin Zhu, Sean O'brien
conference: "Arxiv"
year: 2024
bibkey: knappe2024semantic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07839'}
tags: ['Reinforcement Learning', 'Tools']
---
While large language models (LLMs) have rapidly improved their performance on
a broad number of tasks, they still often fall short on reasoning tasks. As
LLMs become more integrated in diverse real-world tasks, advancing their
reasoning capabilities is crucial to their effectiveness in nuanced, complex
problems. Wang et al.'s self-consistency framework reveals that sampling
multiple rationales before taking a majority vote reliably improves model
performance across various closed-answer reasoning tasks. Standard methods
based on this framework aggregate the final decisions of these rationales but
fail to utilize the semantic information detailed in the step-by-step reasoning
paths. Our work introduces semantic self-consistency, enhancing this approach
by incorporating and analyzing both the reasoning paths of these rationales in
addition to their final decisions before taking a majority vote. These methods
not only improve the reliability of reasoning paths but also cause more robust
performance on complex reasoning tasks.
