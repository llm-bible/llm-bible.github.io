---
layout: publication
title: 'Deriving Coding-specific Sub-models From Llms Using Resource-efficient Pruning'
authors: Laura Puccioni, Alireza Farshin, Mariano Scazzariello, Changjie Wang, Marco Chiesa, Dejan Kostic
conference: "Arxiv"
year: 2025
bibkey: puccioni2025deriving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05248"}
tags: ['Efficiency and Optimization', 'Applications', 'Pruning', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated their exceptional performance
in various complex code generation tasks. However, their broader adoption is
limited by significant computational demands and high resource requirements,
particularly memory and processing power. To mitigate such requirements, model
pruning techniques are used to create more compact models with significantly
fewer parameters. However, current approaches do not focus on the efficient
extraction of programming-language-specific sub-models. In this work, we
explore the idea of efficiently deriving coding-specific sub-models through
unstructured pruning (i.e., Wanda). We investigate the impact of different
domain-specific calibration datasets on pruning outcomes across three distinct
domains and extend our analysis to extracting four language-specific
sub-models: Python, Java, C++, and JavaScript. We are the first to efficiently
extract programming-language-specific sub-models using appropriate calibration
datasets while maintaining acceptable accuracy w.r.t. full models. We are also
the first to provide analytical evidence that domain-specific tasks activate
distinct regions within LLMs, supporting the creation of specialized sub-models
through unstructured pruning. We believe that this work has significant
potential to enhance LLM accessibility for coding by reducing computational
requirements to enable local execution on consumer-grade hardware, and
supporting faster inference times critical for real-time development feedback.
