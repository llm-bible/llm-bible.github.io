---
layout: publication
title: 'Look Before You Leap: Problem Elaboration Prompting Improves Mathematical Reasoning In Large Language Models'
authors: Haoran Liao, Jidong Tian, Shaohua Hu, Hao He, Yaohui Jin
conference: "Arxiv"
year: 2024
bibkey: liao2024look
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.15764'}
tags: ['GPT', 'Efficiency and Optimization', 'Prompting', 'Model Architecture']
---
Large language models (LLMs) still grapple with complex tasks like
mathematical reasoning. Despite significant efforts invested in improving
prefix prompts or reasoning process, the crucial role of problem context might
have been neglected. Accurate recognition of inputs is fundamental for solving
mathematical tasks, as ill-formed problems could potentially mislead LLM's
reasoning. In this study, we propose a new approach named Problem Elaboration
Prompting (PEP) to enhance the mathematical capacities of LLMs. Specifically,
PEP decomposes and elucidates the problem context before reasoning, therefore
enhancing the context modeling and parsing efficiency. Experiments across
datasets and models demonstrate promising performances: (1) PEP demonstrates an
overall enhancement in various mathematical tasks. For instance, with the
GPT-3.5 model, PEP exhibits improvements of 9.93% and 8.80% on GSM8k through
greedy decoding and self-consistency, respectively. (2) PEP can be easily
implemented and integrated with other prompting methods. (3) PEP shows
particular strength in handling distraction problems.
