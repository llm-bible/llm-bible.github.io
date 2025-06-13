---
layout: publication
title: 'HYSYNTH: Context-free LLM Approximation For Guiding Program Synthesis'
authors: Shraddha Barke, Emmanuel Anaya Gonzalez, Saketh Ram Kasibatla, Taylor Berg-kirkpatrick, Nadia Polikarpova
conference: "Arxiv"
year: 2024
bibkey: barke2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.15880'}
tags: ['Reinforcement Learning']
---
Many structured prediction and reasoning tasks can be framed as program
synthesis problems, where the goal is to generate a program in a
domain-specific language (DSL) that transforms input data into the desired
output. Unfortunately, purely neural approaches, such as large language models
(LLMs), often fail to produce fully correct programs in unfamiliar DSLs, while
purely symbolic methods based on combinatorial search scale poorly to complex
problems. Motivated by these limitations, we introduce a hybrid approach, where
LLM completions for a given task are used to learn a task-specific,
context-free surrogate model, which is then used to guide program synthesis. We
evaluate this hybrid approach on three domains, and show that it outperforms
both unguided search and direct sampling from LLMs, as well as existing program
synthesizers.
