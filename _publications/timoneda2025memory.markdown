---
layout: publication
title: 'Memory Is All You Need: Testing How Model Memory Affects LLM Performance In Annotation Tasks'
authors: Joan C. Timoneda, Sebastián Vallejo Vera
conference: "Arxiv"
year: 2025
bibkey: timoneda2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04874"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Few-Shot']
---
Generative Large Language Models (LLMs) have shown promising results in text
annotation using zero-shot and few-shot learning. Yet these approaches do not
allow the model to retain information from previous annotations, making each
response independent from the preceding ones. This raises the question of
whether model memory -- the LLM having knowledge about its own previous
annotations in the same task -- affects performance. In this article, using
OpenAI's GPT-4o and Meta's Llama 3.1 on two political science datasets, we
demonstrate that allowing the model to retain information about its own
previous classifications yields significant performance improvements: between 5
and 25% when compared to zero-shot and few-shot learning. Moreover, memory
reinforcement, a novel approach we propose that combines model memory and
reinforcement learning, yields additional performance gains in three out of our
four tests. These findings have important implications for applied researchers
looking to improve performance and efficiency in LLM annotation tasks.
