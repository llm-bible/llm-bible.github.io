---
layout: publication
title: 'TRIGO: Benchmarking Formal Mathematical Proof Reduction For Generative Language Models'
authors: Jing Xiong, Jianhao Shen, Ye Yuan, Haiming Wang, Yichun Yin, Zhengying Liu, Lin Li, Zhijiang Guo, Qingxing Cao, Yinya Huang, Chuanyang Zheng, Xiaodan Liang, Ming Zhang, Qun Liu
conference: "Arxiv"
year: 2023
bibkey: xiong2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10180"}
tags: ['GPT', 'Model Architecture']
---
Automated theorem proving (ATP) has become an appealing domain for exploring
the reasoning ability of the recent successful generative language models.
However, current ATP benchmarks mainly focus on symbolic inference, but rarely
involve the understanding of complex number combination reasoning. In this
work, we propose TRIGO, an ATP benchmark that not only requires a model to
reduce a trigonometric expression with step-by-step proofs but also evaluates a
generative LM's reasoning ability on formulas and its capability to manipulate,
group, and factor number terms. We gather trigonometric expressions and their
reduced forms from the web, annotate the simplification process manually, and
translate it into the Lean formal language system. We then automatically
generate additional examples from the annotated samples to expand the dataset.
Furthermore, we develop an automatic generator based on Lean-Gym to create
dataset splits of varying difficulties and distributions in order to thoroughly
analyze the model's generalization ability. Our extensive experiments show our
proposed TRIGO poses a new challenge for advanced generative LM's including
GPT-4 which is pre-trained on a considerable amount of open-source formal
theorem-proving language data, and provide a new tool to study the generative
LM's ability on both formal and mathematical reasoning.
