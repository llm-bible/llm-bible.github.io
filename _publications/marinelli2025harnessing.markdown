---
layout: publication
title: 'Harnessing Chain-of-thought Metadata For Task Routing And Adversarial Prompt Detection'
authors: Ryan Marinelli, Josef Pichlmeier, Tamas Bisztray
conference: "Arxiv"
year: 2025
bibkey: marinelli2025harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21464"}
  - {name: "Code", url: "https://github.com/rymarinelli/Number_Of_Thoughts/tree/main"}
tags: ['Prompting', 'Security', 'Has Code', 'Reinforcement Learning']
---
In this work, we propose a metric called Number of Thoughts (NofT) to
determine the difficulty of tasks pre-prompting and support Large Language
Models (LLMs) in production contexts. By setting thresholds based on the number
of thoughts, this metric can discern the difficulty of prompts and support more
effective prompt routing. A 2% decrease in latency is achieved when routing
prompts from the MathInstruct dataset through quantized, distilled versions of
Deepseek with 1.7 billion, 7 billion, and 14 billion parameters. Moreover, this
metric can be used to detect adversarial prompts used in prompt injection
attacks with high efficacy. The Number of Thoughts can inform a classifier that
achieves 95% accuracy in adversarial prompt detection. Our experiments ad
datasets used are available on our GitHub page:
https://github.com/rymarinelli/Number_Of_Thoughts/tree/main.
