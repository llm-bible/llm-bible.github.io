---
layout: publication
title: 'Memorize Or Generalize? Evaluating LLM Code Generation With Evolved Questions'
authors: Wentao Chen, Lizhe Zhang, Li Zhong, Letian Peng, Zilong Wang, Jingbo Shang
conference: "Arxiv"
year: 2025
bibkey: chen2025memorize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02296"}
tags: ['Fine-Tuning', 'Agentic', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) are known to exhibit a memorization phenomenon
in code generation: instead of truly understanding the underlying principles of
a programming problem, they tend to memorize the original prompt and its
solution together in the training. Consequently, when facing variants of the
original problem, their answers very likely resemble the memorized solutions
and fail to generalize. In this paper, we investigate this phenomenon by
designing three evolution strategies to create variants: mutation,
paraphrasing, and code-rewriting. By comparing the performance and AST
similarity of the LLM-generated codes before and after these three evolutions,
we develop a memorization score that positively correlates with the level of
memorization. As expected, as supervised fine-tuning goes on, the memorization
score rises before overfitting, suggesting more severe memorization. We
demonstrate that common mitigation approaches, such as prompt translation and
using evolved variants as data augmentation in supervised learning and
reinforcement learning, either compromise the performance or fail to alleviate
the memorization issue. Therefore, memorization remains a significant challenge
in LLM code generation, highlighting the need for a more effective solution.
