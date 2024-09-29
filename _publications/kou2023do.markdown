---
layout: publication
title: Do Large Language Models Pay Similar Attention Like Human Programmers When Generating Code?
authors: Kou Bonan, Chen Shengmai, Wang Zhijie, Ma Lei, Zhang Tianyi
conference: "Arxiv"
year: 2023
bibkey: kou2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01220"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Interpretability And Explainability', 'Model Architecture']
---
Large Language Models (LLMs) have recently been widely used for code generation. Due to the complexity and opacity of LLMs little is known about how these models generate code. We made the first attempt to bridge this knowledge gap by investigating whether LLMs attend to the same parts of a task description as human programmers during code generation. An analysis of six LLMs including GPT-4 on two popular code generation benchmarks revealed a consistent misalignment between LLMs and programmers attention. We manually analyzed 211 incorrect code snippets and found five attention patterns that can be used to explain many code generation errors. Finally a user study showed that model attention computed by a perturbation-based method is often favored by human programmers. Our findings highlight the need for human-aligned LLMs for better interpretability and programmer trust.
