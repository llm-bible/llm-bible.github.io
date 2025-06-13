---
layout: publication
title: 'Flow2code: Evaluating Large Language Models For Flowchart-based Code Generation Capability'
authors: Mengliang He, Jiayi Zeng, Yankai Jiang, Wei Zhang, Zeming Liu, Xiaoming Shi, Aimin Zhou
conference: "Arxiv"
year: 2025
bibkey: he2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02073'}
  - {name: "Code", url: 'https://github.com/hml-github/Flow2Code'}
tags: ['Has Code', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
While large language models (LLMs) show promise in code generation, existing benchmarks neglect the flowchart-based code generation. To promote further research on flowchart-based code generation, this work presents Flow2Code, a novel benchmark for flowchart-based code generation evaluation. The evaluation dataset spans 15 programming languages and includes 5,622 code segments paired with 16,866 flowcharts of three types: code, UML, and pseudocode. Extensive experiments with 13 multimodal LLMs reveal that current LLMs can not generate code based on flowcharts perfectly. Besides, experiment results show that the supervised fine-tuning technique contributes greatly to the models' performance. We publicly release our code and datasets at https://github.com/hml-github/Flow2Code.
