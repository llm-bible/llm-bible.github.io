---
layout: publication
title: 'Optimizing Llms With Direct Preferences: A Data Efficiency Perspective'
authors: Pietro Bernardelle, Gianluca Demartini
conference: "Arxiv"
year: 2024
bibkey: bernardelle2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16586"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Aligning the output of Large Language Models (LLMs) with human preferences
(e.g., by means of reinforcement learning with human feedback, or RLHF) is
essential for ensuring their effectiveness in real-world scenarios. Despite
significant advancements in LLM alignment techniques, the impact of different
type of preference data on model performance has yet to be systematically
explored. In this study, we investigate the scalability, data efficiency, and
effectiveness of Direct Preference Optimization (DPO) in fine-tuning
pre-trained LLMs, aiming to reduce their dependency on extensive amounts of
preference data, which is expensive to collect. We (1) systematically compare
the performance of models fine-tuned with varying percentages of a combined
preference judgement dataset to define the improvement curve of DPO and assess
its effectiveness in data-constrained environments; and (2) provide insights
for the development of an optimal approach for selective preference data usage.
Our study reveals that increasing the amount of data used for training
generally enhances and stabilizes model performance. Moreover, the use of a
combination of diverse datasets significantly improves model effectiveness.
Furthermore, when models are trained separately using different types of
prompts, models trained with conversational prompts outperformed those trained
with question answering prompts.
