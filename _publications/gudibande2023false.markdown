---
layout: publication
title: 'The False Promise Of Imitating Proprietary Llms'
authors: Gudibande Arnav, Wallace Eric, Snell Charlie, Geng Xinyang, Liu Hao, Abbeel Pieter, Levine Sergey, Song Dawn
conference: "Arxiv"
year: 2023
bibkey: gudibande2023false
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15717"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
An emerging method to cheaply improve a weaker language model is to finetune it on outputs from a stronger model, such as a proprietary system like ChatGPT (e.g., Alpaca, Self-Instruct, and others). This approach looks to cheaply imitate the proprietary model's capabilities using a weaker open-source model. In this work, we critically analyze this approach. We first finetune a series of LMs that imitate ChatGPT using varying base model sizes (1.5B--13B), data sources, and imitation data amounts (0.3M--150M tokens). We then evaluate the models using crowd raters and canonical NLP benchmarks. Initially, we were surprised by the output quality of our imitation models -- they appear far better at following instructions, and crowd workers rate their outputs as competitive with ChatGPT. However, when conducting more targeted automatic evaluations, we find that imitation models close little to none of the gap from the base LM to ChatGPT on tasks that are not heavily supported in the imitation data. We show that these performance discrepancies may slip past human raters because imitation models are adept at mimicking ChatGPT's style but not its factuality. Overall, we conclude that model imitation is a false promise: there exists a substantial capabilities gap between open and closed LMs that, with current methods, can only be bridged using an unwieldy amount of imitation data or by using more capable base LMs. In turn, we argue that the highest leverage action for improving open-source models is to tackle the difficult challenge of developing better base LMs, rather than taking the shortcut of imitating proprietary systems.
