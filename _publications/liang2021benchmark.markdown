---
layout: publication
title: Lyra: A Benchmark For Turducken-style Code Generation
authors: Liang Qingyuan, Sun Zeyu, Zhu Qihao, Zhang Wenjie, Yu Lian, Xiong Yingfei, Zhang Lu
conference: "Arxiv"
year: 2021
bibkey: liang2021benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.12144"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Recently neural techniques have been used to generate source code automatically. While promising for declarative languages these approaches achieve much poorer performance on datasets for imperative languages. Since a declarative language is typically embedded in an imperative language (i.e. the turducken-style programming) in real-world software development the promising results on declarative languages can hardly lead to significant reduction of manual software development efforts. In this paper we define a new code generation task given a natural language comment this task aims to generate a program in a base imperative language with an embedded declarative language. To our knowledge this is the first turducken-style code generation task. For this task we present Lyra a dataset in Python with embedded SQL. This dataset contains 2000 carefully annotated database manipulation programs from real-world projects. Each program is paired with both a Chinese comment and an English comment. In our experiment we adopted Transformer BERT-style and GPT-style models as baselines. In the best setting the generation performance of GPT-style models is better than others where the AST exact matching accuracy is 2437; and 25.537; when using Chinese and English comments respectively. Therefore we believe that Lyra provides a new challenge for code generation. Yet overcoming this challenge may significantly boost the applicability of code generation techniques for real-world software development.
