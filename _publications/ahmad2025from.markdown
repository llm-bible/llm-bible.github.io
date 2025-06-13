---
layout: publication
title: 'From Output To Evaluation: Does Raw Instruction-tuned Code Llms Output Suffice For Fill-in-the-middle Code Generation?'
authors: Wasi Uddin Ahmad, Somshubra Majumdar, Boris Ginsburg
conference: "Arxiv"
year: 2025
bibkey: ahmad2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18789'}
tags: ['Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Post-processing is crucial for the automatic evaluation of LLMs in fill-in-the-middle (FIM) code generation due to the frequent presence of extraneous code in raw outputs. This extraneous generation suggests a lack of awareness regarding output boundaries, requiring truncation for effective evaluation. The determination of an optimal truncation strategy, however, often proves intricate, particularly when the scope includes several programming languages. This study investigates the necessity of post-processing instruction-tuned LLM outputs. Our findings reveal that supervised fine-tuning significantly enhances FIM code generation, enabling LLMs to generate code that seamlessly integrates with the surrounding context. Evaluating our fine-tuned \texttt\{Qwen2.5-Coder\} (base and instruct) models on HumanEval Infilling and SAFIM benchmarks demonstrates improved performances without post-processing, especially when the *middle* consist of complete lines. However, post-processing of the LLM outputs remains necessary when the *middle* is a random span of code.
