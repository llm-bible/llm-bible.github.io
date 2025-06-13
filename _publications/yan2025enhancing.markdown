---
layout: publication
title: 'Mathfimer: Enhancing Mathematical Reasoning By Expanding Reasoning Steps Through Fill-in-the-middle Task'
authors: Yuchen Yan, Yongliang Shen, Yang Liu, Jin Jiang, Xin Xu, Mengdi Zhang, Jian Shao, Yueting Zhuang
conference: "Arxiv"
year: 2025
bibkey: yan2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11684'}
tags: ['Tools', 'Training Techniques']
---
Mathematical reasoning represents a critical frontier in advancing large
language models (LLMs). While step-by-step approaches have emerged as the
dominant paradigm for mathematical problem-solving in LLMs, the quality of
reasoning steps in training data fundamentally constrains the performance of
the models. Recent studies has demonstrated that more detailed intermediate
steps can enhance model performance, yet existing methods for step expansion
either require more powerful external models or incur substantial computational
costs. In this paper, we introduce MathFimer, a novel framework for
mathematical reasoning step expansion inspired by the "Fill-in-the-middle" task
from code completion. By decomposing solution chains into prefix-suffix pairs
and training models to reconstruct missing intermediate steps, we develop a
specialized model, MathFimer-7B, on our carefully curated NuminaMath-FIM
dataset. We then apply these models to enhance existing mathematical reasoning
datasets by inserting detailed intermediate steps into their solution chains,
creating MathFimer-expanded versions. Through comprehensive experiments on
multiple mathematical reasoning datasets, including MathInstruct, MetaMathQA
and etc., we demonstrate that models trained on MathFimer-expanded data
consistently outperform their counterparts trained on original data across
various benchmarks such as GSM8K and MATH. Our approach offers a practical,
scalable solution for enhancing mathematical reasoning capabilities in LLMs
without relying on powerful external models or expensive inference procedures.
