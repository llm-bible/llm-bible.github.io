---
layout: publication
title: 'LIDA: A Tool For Automatic Generation Of Grammar-agnostic Visualizations And Infographics Using Large Language Models'
authors: Victor Dibia
conference: "Arxiv"
year: 2023
citations: 41
bibkey: dibia2023tool
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.02927'}
  - {name: "Code", url: 'https://microsoft.github.io/lida/'}
tags: ['Has Code', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Systems that support users in the automatic creation of visualizations must
address several subtasks - understand the semantics of data, enumerate relevant
visualization goals and generate visualization specifications. In this work, we
pose visualization generation as a multi-stage generation problem and argue
that well-orchestrated pipelines based on large language models (LLMs) such as
ChatGPT/GPT-4 and image generation models (IGMs) are suitable to addressing
these tasks. We present LIDA, a novel tool for generating grammar-agnostic
visualizations and infographics. LIDA comprises of 4 modules - A SUMMARIZER
that converts data into a rich but compact natural language summary, a GOAL
EXPLORER that enumerates visualization goals given the data, a VISGENERATOR
that generates, refines, executes and filters visualization code and an
INFOGRAPHER module that yields data-faithful stylized graphics using IGMs. LIDA
provides a python api, and a hybrid user interface (direct manipulation and
multilingual natural language) for interactive chart, infographics and data
story generation. Learn more about the project here -
https://microsoft.github.io/lida/
