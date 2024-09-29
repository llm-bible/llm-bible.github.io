---
layout: publication
title: 'Investigating Symbolic Capabilities Of Large Language Models'
authors: Dave Neisarg, Kifer Daniel, Giles C. Lee, Mali Ankur
conference: "Arxiv"
year: 2024
bibkey: dave2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13209"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Prompting techniques have significantly enhanced the capabilities of Large Language Models (LLMs) across various complex tasks including reasoning planning and solving math word problems. However most research has predominantly focused on language-based reasoning and word problems often overlooking the potential of LLMs in handling symbol-based calculations and reasoning. This study aims to bridge this gap by rigorously evaluating LLMs on a series of symbolic tasks such as addition multiplication modulus arithmetic numerical precision and symbolic counting. Our analysis encompasses eight LLMs including four enterprise-grade and four open-source models of which three have been pre-trained on mathematical tasks. The assessment framework is anchored in Chomskys Hierarchy providing a robust measure of the computational abilities of these models. The evaluation employs minimally explained prompts alongside the zero-shot Chain of Thoughts technique allowing models to navigate the solution process autonomously. The findings reveal a significant decline in LLMs performance on context-free and context-sensitive symbolic tasks as the complexity represented by the number of symbols increases. Notably even the fine-tuned GPT3.5 exhibits only marginal improvements mirroring the performance trends observed in other models. Across the board all models demonstrated a limited generalization ability on these symbol-intensive tasks. This research underscores LLMs challenges with increasing symbolic complexity and highlights the need for specialized training memory and architectural adjustments to enhance their proficiency in symbol-based reasoning tasks.
