---
layout: publication
title: 'Large Language Models'' Reasoning Stalls: An Investigation Into The Capabilities Of Frontier Models'
authors: Lachlan Mcginness, Peter Baumgartner
conference: "Arxiv"
year: 2025
bibkey: mcginness2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19676"}
tags: ['Prompting', 'Training Techniques', 'GPT', 'Model Architecture']
---
Empirical methods to examine the capability of Large Language Models (LLMs) to use Automated Theorem Prover (ATP) reasoning strategies are studied. We evaluate the performance of State of the Art models from December 2023 and August 2024 on PRONTOQA steamroller reasoning problems. For that, we develop methods for assessing LLM response accuracy and correct answer correlation.
  Our results show that progress in improving LLM reasoning abilities has stalled over the nine month period. By tracking completion tokens, we show that almost all improvement in reasoning ability since GPT-4 was released can be attributed to either hidden system prompts or the training of models to automatically use generic Chain of Thought prompting strategies. Among the ATP reasoning strategies tried, we found that current frontier LLMs are best able to follow the bottom-up (also known as forward-chaining) strategy. A low positive correlation was found between an LLM response containing correct reasoning and arriving at the correct conclusion.
