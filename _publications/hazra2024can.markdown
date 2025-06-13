---
layout: publication
title: 'Can Large Language Models Reason? A Characterization Via 3-SAT'
authors: Rishi Hazra, Gabriele Venturato, Pedro Zuidberg Dos Martires, Luc De Raedt
conference: "Arxiv"
year: 2024
bibkey: hazra2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07215"}
tags: ['Reinforcement Learning']
---
Large Language Models (LLMs) have been touted as AI models possessing
advanced reasoning abilities. However, recent works have shown that LLMs often
bypass true reasoning using shortcuts, sparking skepticism. To study the
reasoning capabilities in a principled fashion, we adopt a computational theory
perspective and propose an experimental protocol centered on 3-SAT -- the
prototypical NP-complete problem lying at the core of logical reasoning and
constraint satisfaction tasks. Specifically, we examine the phase transitions
in random 3-SAT and characterize the reasoning abilities of LLMs by varying the
inherent hardness of the problem instances. Our experimental evidence shows
that LLMs are incapable of performing true reasoning, as required for solving
3-SAT problems. Moreover, we observe significant performance variation based on
the inherent hardness of the problems -- performing poorly on harder instances
and vice versa. Importantly, we show that integrating external reasoners can
considerably enhance LLM performance. By following a principled experimental
protocol, our study draws concrete conclusions and moves beyond the anecdotal
evidence often found in LLM reasoning research.
