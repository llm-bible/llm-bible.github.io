---
layout: publication
title: Towards Neural Functional Program Evaluation
authors: Scholak Torsten, Pilault Jonathan, Velez-ginorio Joey
conference: "Arxiv"
year: 2021
bibkey: scholak2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.04630"}
  - {name: "Code", url: "https://github.com/ElementAI/neural-interpreters"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
This paper explores the capabilities of current transformer-based language models for program evaluation of simple functional programming languages. We introduce a new program generation mechanism that allows control over syntactic sugar for semantically equivalent programs. T5 experiments reveal that neural functional program evaluation performs surprisingly well achieving high 9037; exact program match scores for most in-distribution and out-of-distribution tests. Using pretrained T5 weights has significant advantages over random initialization. We present and evaluate on three datasets to study generalization abilities that are specific to functional programs based on type function composition and reduction steps. Code and data are publicly available at https://github.com/ElementAI/neural-interpreters."
