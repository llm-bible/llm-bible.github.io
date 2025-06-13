---
layout: publication
title: 'PDL: A Declarative Prompt Programming Language'
authors: Mandana Vaziri, Louis Mandel, Claudio Spiess, Martin Hirzel
conference: "Arxiv"
year: 2024
bibkey: vaziri2024declarative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19135'}
tags: ['Agentic', 'RAG', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) have taken the world by storm by making many
previously difficult uses of AI feasible. LLMs are controlled via highly
expressive textual prompts and return textual answers. Unfortunately, this
unstructured text as input and output makes LLM-based applications brittle.
This motivates the rise of prompting frameworks, which mediate between LLMs and
the external world. However, existing prompting frameworks either have a high
learning curve or take away control over the exact prompts from the developer.
To overcome this dilemma, this paper introduces the Prompt Declaration Language
(PDL). PDL is a simple declarative data-oriented language that puts prompts at
the forefront, based on YAML. PDL works well with many LLM platforms and LLMs.
It supports writing interactive applications that call LLMs and tools, and
makes it easy to implement common use-cases such as chatbots, RAG, or agents.
We hope PDL will make prompt programming simpler, less brittle, and more
enjoyable.
