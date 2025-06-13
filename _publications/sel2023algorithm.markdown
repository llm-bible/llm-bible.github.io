---
layout: publication
title: 'Algorithm Of Thoughts: Enhancing Exploration Of Ideas In Large Language Models'
authors: Bilgehan Sel, Ahmad Al-tawaha, Vanshaj Khattar, Ruoxi Jia, Ming Jin
conference: "Arxiv"
year: 2023
bibkey: sel2023algorithm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10379"}
  - {name: "Code", url: "https://algorithm-of-thoughts.github.io"}
tags: ['Fine-Tuning', 'Has Code', 'Reinforcement Learning']
---
Current literature, aiming to surpass the "Chain-of-Thought" approach, often
resorts to external modi operandi involving halting, modifying, and then
resuming the generation process to boost Large Language Models' (LLMs)
reasoning capacities. Due to their myopic perspective, they escalate the number
of query requests, leading to increased costs, memory, and computational
overheads. Addressing this, we propose the Algorithm of Thoughts -- a novel
strategy that propels LLMs through algorithmic reasoning pathways. By employing
algorithmic examples fully in-context, this overarching view of the whole
process exploits the innate recurrence dynamics of LLMs, expanding their idea
exploration with merely one or a few queries. Our technique outperforms earlier
single-query methods and even more recent multi-query strategies that employ an
extensive tree search algorithms while using significantly fewer tokens.
Intriguingly, our results suggest that instructing an LLM using an algorithm
can lead to performance surpassing that of the algorithm itself, hinting at
LLM's inherent ability to weave its intuition into optimized searches. We probe
into the underpinnings of our method's efficacy and its nuances in application.
The code and related content can be found in:
https://algorithm-of-thoughts.github.io.
