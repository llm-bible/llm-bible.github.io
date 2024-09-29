---
layout: publication
title: Leveraging Large Language Models To Generate Answer Set Programs
authors: Ishay Adam, Yang Zhun, Lee Joohyung
conference: "Arxiv"
year: 2023
bibkey: ishay2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.07699"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG']
---
Large language models (LLMs) such as GPT45;3 and GPT45;4 have demonstrated exceptional performance in various natural language processing tasks and have shown the ability to solve certain reasoning problems. However their reasoning capabilities are limited and relatively shallow despite the application of various prompting techniques. In contrast formal logic is adept at handling complex reasoning but translating natural language descriptions into formal logic is a challenging task that non45;experts struggle with. This paper proposes a neuro45;symbolic method that combines the strengths of large language models and answer set programming. Specifically we employ an LLM to transform natural language descriptions of logic puzzles into answer set programs. We carefully design prompts for an LLM to convert natural language descriptions into answer set programs in a step by step manner. Surprisingly with just a few in45;context learning examples LLMs can generate reasonably complex answer set programs. The majority of errors made are relatively simple and can be easily corrected by humans thus enabling LLMs to effectively assist in the creation of answer set programs.
