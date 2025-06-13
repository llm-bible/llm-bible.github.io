---
layout: publication
title: 'Steering Conversational Large Language Models For Long Emotional Support Conversations'
authors: Navid Madani, Sougata Saha, Rohini Srihari
conference: "Arxiv"
year: 2024
bibkey: madani2024steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10453"}
tags: ['Attention Mechanism', 'Prompting', 'Model Architecture', 'Reinforcement Learning']
---
In this study, we address the challenge of enabling large language models
(LLMs) to consistently adhere to emotional support strategies in extended
conversations. We focus on the steerability of the Llama-2 and Llama-3 suite of
models, examining their ability to maintain these strategies throughout
interactions. To assess this, we introduce the Strategy Relevant Attention
(SRA) metric, which quantifies the model's adherence to the prompted strategy
through attention maps. To facilitate our study, we create a
strategy-conditioned synthetic conversational dataset derived from the ESConv
dataset. We also propose various baselines informed by our proposed SRA metric
to address the challenge and propose a fine-tuned model that significantly
enhances the steerability of the base model in following the strategy
throughout the conversation. The code and data are publicly available on our
GitHub.
