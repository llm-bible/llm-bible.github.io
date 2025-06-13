---
layout: publication
title: 'Zero-shot Slot Filling In The Age Of Llms For Dialogue Systems'
authors: Mansi Rana, Kadri Hacioglu, Sindhuja Gopalan, Maragathamani Boothalingam
conference: "Arxiv"
year: 2024
bibkey: rana2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18980"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Distillation', 'Applications']
---
Zero-shot slot filling is a well-established subtask of Natural Language
Understanding (NLU). However, most existing methods primarily focus on
single-turn text data, overlooking the unique complexities of conversational
dialogue. Conversational data is highly dynamic, often involving abrupt topic
shifts, interruptions, and implicit references that make it difficult to
directly apply zero-shot slot filling techniques, even with the remarkable
capabilities of large language models (LLMs). This paper addresses these
challenges by proposing strategies for automatic data annotation with slot
induction and black-box knowledge distillation (KD) from a teacher LLM to a
smaller model, outperforming vanilla LLMs on internal datasets by 26% absolute
increase in F1 score. Additionally, we introduce an efficient system
architecture for call center product settings that surpasses off-the-shelf
extractive models by 34% relative F1 score, enabling near real-time inference
on dialogue streams with higher accuracy, while preserving low latency.
