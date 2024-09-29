---
layout: publication
title: Generating Data For Symbolic Language With Large Language Models
authors: Ye Jiacheng, Li Chengzu, Kong Lingpeng, Yu Tao
conference: "Arxiv"
year: 2023
bibkey: ye2023generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13917"}
  - {name: "Code", url: "https://github.com/HKUNLP/SymGen&#125;&#123;https://github.com/HKUNLP/SymGen&#125;"}
tags: ['Applications', 'Has Code', 'Prompting', 'Training Techniques']
---
While large language models (LLMs) bring not only performance but also complexity recent work has started to turn LLMs into data generators rather than task inferencers where another affordable task model is trained for efficient deployment and inference. However such an approach has primarily been applied to natural language tasks and has not yet been explored for symbolic language tasks with complex structured outputs (e.g. semantic parsing and code generation). In this paper we propose SymGen which utilizes LLMs for generating various annotation45;expensive symbolic language data. SymGen consists of an informative prompt to steer generation and an agreement45;based verifier to improve data correctness. We conduct extensive experiments on six symbolic language tasks across various settings. Compared with the LLMs we demonstrate the 137;45;sized task model can achieve comparable or better performance largely cutting inference and deployment costs. We also show that generated data with only a few human demonstrations can be as effective as over 10 times the amount of human45;annotated data when training the task model saving a considerable amount of annotation effort. SymGen sheds new light on data generation for complex tasks and we release the code at href123;https://github.com/HKUNLP/SymGen&#125;&#123;https://github.com/HKUNLP/SymGen&#125;.
