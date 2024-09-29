---
layout: publication
title: Selecting Better Samples from Pre-trained LLMs A Case Study on Question Generation
authors: Yuan Xingdi, Wang Tong, Wang Yen-hsiang, Fine Emery, Abdelghani Rania, Lucas Pauline, Sauzéon Hélène, Oudeyer Pierre-yves
conference: "Arxiv"
year: 2022
bibkey: yuan2022selecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.11000"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) have in recent years demonstrated impressive prowess in natural language generation. A common practice to improve generation diversity is to sample multiple outputs from the model. However there lacks a simple and robust way of selecting the best output from these stochastic samples. As a case study framed in the context of question generation we propose two prompt-based approaches to selecting high-quality questions from a set of LLM-generated candidates. Our method works under the constraints of 1) a black-box (non-modifiable) question generation model and 2) lack of access to human-annotated references -- both of which are realistic limitations for real-world deployment of LLMs. With automatic as well as human evaluations we empirically demonstrate that our approach can effectively select questions of higher qualities than greedy generation.
