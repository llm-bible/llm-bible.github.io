---
layout: publication
title: 'Personality-guided Code Generation Using Large Language Models'
authors: Yaoqi Guo, Zhenpeng Chen, Jie M. Zhang, Yang Liu, Yun Ma
conference: "Arxiv"
year: 2024
bibkey: guo2024personality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00006"}
  - {name: "Code", url: "https://github.com/IanWalls/Persona-Code"}
tags: ['Applications', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Prompting']
---
Code generation, the automatic creation of source code from natural language descriptions, has garnered significant attention due to its potential to streamline software development. Inspired by research that links task-personality alignment with improved development outcomes, we conduct an empirical study on personality-guided code generation using large language models (LLMs). Specifically, we investigate how emulating personality traits appropriate to the coding tasks affects LLM performance. We extensively evaluate this approach using seven widely adopted LLMs across four representative datasets. Our results show that personality guidance significantly enhances code generation accuracy, with improved pass rates in 23 out of 28 LLM-dataset combinations. Notably, in 11 cases, the improvement exceeds 5%, and in 5 instances, it surpasses 10%, with the highest gain reaching 12.9%. Additionally, personality guidance can be easily integrated with other prompting strategies to further boost performance. We open-source our code and data at https://github.com/IanWalls/Persona-Code.
