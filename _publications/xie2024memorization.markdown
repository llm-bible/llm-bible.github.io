---
layout: publication
title: 'On Memorization Of Large Language Models In Logical Reasoning'
authors: Chulin Xie, Yangsibo Huang, Chiyuan Zhang, Da Yu, Xinyun Chen, Bill Yuchen Lin, Bo Li, Badih Ghazi, Ravi Kumar
conference: "Arxiv"
year: 2024
bibkey: xie2024memorization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23123"}
  - {name: "Code", url: "https://memkklogic.github.io"}
tags: ['Fine-Tuning', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) achieve good performance on challenging
reasoning benchmarks, yet could also make basic reasoning mistakes. This
contrasting behavior is puzzling when it comes to understanding the mechanisms
behind LLMs' reasoning capabilities. One hypothesis is that the increasingly
high and nearly saturated performance on common reasoning benchmarks could be
due to the memorization of similar problems. In this paper, we systematically
investigate this hypothesis with a quantitative measurement of memorization in
reasoning tasks, using a dynamically generated logical reasoning benchmark
based on Knights and Knaves (K&K) puzzles. We find that LLMs could interpolate
and memorize the training puzzles (achieving near-perfect accuracy) after
fine-tuning, yet they struggle with slight variations of these puzzles. On the
other hand, we show that while fine-tuning leads to heavy memorization, it also
consistently improves generalization performance. Through in-depth analyses
with perturbation tests, cross difficulty-level transferability, probing model
internals, and fine-tuning with wrong answers, we establish that LLMs develop
reasoning skills on K&K puzzles alongside memorization. Finally, our analysis
based on a per-sample memorization score sheds light on how LLMs switch between
reasoning and memorization when solving logical puzzles. Our code and data are
available at https://memkklogic.github.io.
