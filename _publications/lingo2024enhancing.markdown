---
layout: publication
title: 'Enhancing LLM Problem Solving With REAP: Reflection, Explicit Problem Deconstruction, And Advanced Prompting'
authors: Ryan Lingo, Martin Arroyo, Rajeev Chhajer
conference: "Arxiv"
year: 2024
bibkey: lingo2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09415"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'GPT', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have transformed natural language processing,
yet improving their problem-solving capabilities, particularly for complex,
reasoning-intensive tasks, remains a persistent challenge. This paper
introduces the REAP (Reflection, Explicit Problem Deconstruction, and Advanced
Prompting) method, an innovative approach within the dynamic context generation
framework. REAP guides LLMs through reflection on the query, deconstructing it
into manageable components, and generating relevant context to enhance the
solution process. We evaluated REAP using a dataset designed to expose LLM
limitations, comparing zero-shot prompting with REAP-enhanced prompts across
six state-of-the-art models: OpenAI's o1-preview, o1-mini, GPT-4o, GPT-4o-mini,
Google's Gemini 1.5 Pro, and Claude 3.5 Sonnet. The results demonstrate notable
performance gains, with o1-mini improving by 40.97%, GPT-4o by 66.26%, and
GPT-4o-mini by 112.93%. Despite the already strong baseline performance of
OpenAI's o1-preview, modest gains were observed. Beyond performance
improvements, REAP offers a cost-effective solution; for example, GPT-4o-mini,
which is approximately 100 times cheaper than o1-preview, delivered competitive
results. REAP also improves the clarity of model outputs, making it easier for
humans to understand the reasoning behind the results and simplifying the
process of identifying and addressing any issues. These findings demonstrate
REAP's potential to greatly improve the capabilities of LLMs, providing both
better performance and increased cost-efficiency across a wide range of
applications.
