---
layout: publication
title: 'Have Large Language Models Learned To Reason? A Characterization Via 3-SAT Phase Transition'
authors: Rishi Hazra, Gabriele Venturato, Pedro Zuidberg Dos Martires, Luc De Raedt
conference: "Arxiv"
year: 2025
bibkey: hazra2025have
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.03930'}
tags: ['Reinforcement Learning', 'GPT', 'Pretraining Methods']
---
Large Language Models (LLMs) have been touted as AI models possessing
advanced reasoning abilities. In theory, autoregressive LLMs with
Chain-of-Thought (CoT) can perform more serial computations to solve complex
reasoning tasks. However, recent studies suggest that, despite this capacity,
LLMs do not truly learn to reason but instead fit on statistical features. To
study the reasoning capabilities in a principled fashion, we adopt a
computational theory perspective and propose an experimental protocol centered
on 3-SAT -- the prototypical NP-complete problem lying at the core of logical
reasoning and constraint satisfaction tasks. Specifically, we examine the phase
transitions in random 3-SAT and characterize the reasoning abilities of
state-of-the-art LLMs by varying the inherent hardness of the problem
instances. By comparing DeepSeek R1 with other LLMs, our findings reveal two
key insights (1) LLM accuracy drops significantly on harder instances,
suggesting all current models struggle when statistical shortcuts are
unavailable (2) Unlike other LLMs, R1 shows signs of having learned the
underlying reasoning. Following a principled experimental protocol, our study
moves beyond the benchmark-driven evidence often found in LLM reasoning
research. Our findings highlight important gaps and suggest clear directions
for future research.
