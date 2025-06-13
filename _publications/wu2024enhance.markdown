---
layout: publication
title: 'Enhance Reasoning For Large Language Models In The Game Werewolf'
authors: Shuang Wu, Liwen Zhu, Tao Yang, Shiwei Xu, Qiang Fu, Yang Wei, Haobo Fu
conference: "Arxiv"
year: 2024
bibkey: wu2024enhance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02330"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
This paper presents an innovative framework that integrates Large Language
Models (LLMs) with an external Thinker module to enhance the reasoning
capabilities of LLM-based agents. Unlike augmenting LLMs with prompt
engineering, Thinker directly harnesses knowledge from databases and employs
various optimization techniques. The framework forms a reasoning hierarchy
where LLMs handle intuitive System-1 tasks such as natural language processing,
while the Thinker focuses on cognitive System-2 tasks that require complex
logical analysis and domain-specific knowledge. Our framework is presented
using a 9-player Werewolf game that demands dual-system reasoning. We introduce
a communication protocol between LLMs and the Thinker, and train the Thinker
using data from 18800 human sessions and reinforcement learning. Experiments
demonstrate the framework's effectiveness in deductive reasoning, speech
generation, and online game evaluation. Additionally, we fine-tune a 6B LLM to
surpass GPT4 when integrated with the Thinker. This paper also contributes the
largest dataset for social deduction games to date.
