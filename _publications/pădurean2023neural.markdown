---
layout: publication
title: "Neural Task Synthesis For Visual Programming"
authors: Pădurean Victor-alexandru, Tzannetos Georgios, Singla Adish
conference: "Arxiv"
year: 2023
bibkey: pădurean2023neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18342"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Generative neural models hold great promise in enhancing programming education by synthesizing new content. We seek to design neural models that can automatically generate programming tasks for a given specification in the context of visual programming domains. Despite the recent successes of large generative models like GPT-4 our initial results show that these models are ineffective in synthesizing visual programming tasks and struggle with logical and spatial reasoning. We propose a novel neuro-symbolic technique NeurTaskSyn that can synthesize programming tasks for a specification given in the form of desired programming concepts exercised by its solution code and constraints on the visual task. NeurTaskSyn has two components the first component is trained via imitation learning procedure to generate possible solution codes and the second component is trained via reinforcement learning procedure to guide an underlying symbolic execution engine that generates visual tasks for these codes. We demonstrate the effectiveness of NeurTaskSyn through an extensive empirical evaluation and a qualitative study on reference tasks taken from the Hour of Code Classic Maze challenge by Code-dot-org and the Intro to Programming with Karel course by CodeHS-dot-com.
