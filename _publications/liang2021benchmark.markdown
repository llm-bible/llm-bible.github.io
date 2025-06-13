---
layout: publication
title: 'Lyra: A Benchmark For Turducken-style Code Generation'
authors: Qingyuan Liang, Zeyu Sun, Qihao Zhu, Wenjie Zhang, Lian Yu, Yingfei Xiong, Lu Zhang
conference: "Proceedings of the Thirty-First International Joint Conference on Artificial Intelligence 2022 Main Track. Pages 4238-4244"
year: 2021
bibkey: liang2021benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.12144"}
tags: ['Transformer', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'BERT']
---
Recently, neural techniques have been used to generate source code
automatically. While promising for declarative languages, these approaches
achieve much poorer performance on datasets for imperative languages. Since a
declarative language is typically embedded in an imperative language (i.e., the
turducken-style programming) in real-world software development, the promising
results on declarative languages can hardly lead to significant reduction of
manual software development efforts. In this paper, we define a new code
generation task: given a natural language comment, this task aims to generate a
program in a base imperative language with an embedded declarative language. To
our knowledge, this is the first turducken-style code generation task. For this
task, we present Lyra: a dataset in Python with embedded SQL. This dataset
contains 2,000 carefully annotated database manipulation programs from
real-world projects. Each program is paired with both a Chinese comment and an
English comment. In our experiment, we adopted Transformer, BERT-style, and
GPT-style models as baselines. In the best setting, the generation performance
of GPT-style models is better than others, where the AST exact matching
accuracy is 24% and 25.5% when using Chinese and English comments,
respectively. Therefore, we believe that Lyra provides a new challenge for code
generation. Yet, overcoming this challenge may significantly boost the
applicability of code generation techniques for real-world software
development.
