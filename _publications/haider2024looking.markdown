---
layout: publication
title: "Looking Into Black Box Code Language Models"
authors: Haider Muhammad Umair, Farooq Umar, Siddique A. B., Marron Mark
conference: "Arxiv"
year: 2024
bibkey: haider2024looking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04868"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Language Models (LMs) have shown their application for tasks pertinent to code and several code~LMs have been proposed recently. The majority of the studies in this direction only focus on the improvements in performance of the LMs on different benchmarks whereas LMs are considered black boxes. Besides this a handful of works attempt to understand the role of attention layers in the code~LMs. Nonetheless feed-forward layers remain under-explored which consist of two-thirds of a typical transformer models parameters. In this work we attempt to gain insights into the inner workings of code language models by examining the feed-forward layers. To conduct our investigations we use two state-of-the-art code~LMs Codegen-Mono and Ploycoder and three widely used programming languages Java Go and Python. We focus on examining the organization of stored concepts the editability of these concepts and the roles of different layers and input context size variations for output generation. Our empirical findings demonstrate that lower layers capture syntactic patterns while higher layers encode abstract concepts and semantics. We show concepts of interest can be edited within feed-forward layers without compromising code~LM performance. Additionally we observe initial layers serve as thinking layers while later layers are crucial for predicting subsequent code tokens. Furthermore we discover earlier layers can accurately predict smaller contexts but larger contexts need critical later layers contributions. We anticipate these findings will facilitate better understanding debugging and testing of code~LMs.
