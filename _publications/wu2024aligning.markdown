---
layout: publication
title: 'Aligning Llms With Individual Preferences Via Interaction'
authors: Shujin Wu, May Fung, Cheng Qian, Jeonghwan Kim, Dilek Hakkani-tur, Heng Ji
conference: "Arxiv"
year: 2024
bibkey: wu2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03642"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
As large language models (LLMs) demonstrate increasingly advanced
capabilities, aligning their behaviors with human values and preferences
becomes crucial for their wide adoption. While previous research focuses on
general alignment to principles such as helpfulness, harmlessness, and honesty,
the need to account for individual and diverse preferences has been largely
overlooked, potentially undermining customized human experiences. To address
this gap, we train LLMs that can ''interact to align'', essentially cultivating
the meta-skill of LLMs to implicitly infer the unspoken personalized
preferences of the current user through multi-turn conversations, and then
dynamically align their following behaviors and responses to these inferred
preferences. Our approach involves establishing a diverse pool of 3,310
distinct user personas by initially creating seed examples, which are then
expanded through iterative self-generation and filtering. Guided by distinct
user personas, we leverage multi-LLM collaboration to develop a multi-turn
preference dataset containing 3K+ multi-turn conversations in tree structures.
Finally, we apply supervised fine-tuning and reinforcement learning to enhance
LLMs using this dataset. For evaluation, we establish the ALOE (ALign With
CustOmized PrEferences) benchmark, consisting of 100 carefully selected
examples and well-designed metrics to measure the customized alignment
performance during conversations. Experimental results demonstrate the
effectiveness of our method in enabling dynamic, personalized alignment via
interaction.
