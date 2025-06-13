---
layout: publication
title: 'Step-kto: Optimizing Mathematical Reasoning Through Stepwise Binary Feedback'
authors: Yen-ting Lin, Di Jin, Tengyu Xu, Tianhao Wu, Sainbayar Sukhbaatar, Chen Zhu, Yun He, Yun-nung Chen, Jason Weston, Yuandong Tian, Arash Rahnama, Sinong Wang, Hao Ma, Han Fang
conference: "Arxiv"
year: 2025
bibkey: lin2025step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10799"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting']
---
Large language models (LLMs) have recently demonstrated remarkable success in
mathematical reasoning. Despite progress in methods like chain-of-thought
prompting and self-consistency sampling, these advances often focus on final
correctness without ensuring that the underlying reasoning process is coherent
and reliable. This paper introduces Step-KTO, a training framework that
combines process-level and outcome-level binary feedback to guide LLMs toward
more trustworthy reasoning trajectories. By providing binary evaluations for
both the intermediate reasoning steps and the final answer, Step-KTO encourages
the model to adhere to logical progressions rather than relying on superficial
shortcuts. Our experiments on challenging mathematical benchmarks show that
Step-KTO significantly improves both final answer accuracy and the quality of
intermediate reasoning steps. For example, on the MATH-500 dataset, Step-KTO
achieves a notable improvement in Pass@1 accuracy over strong baselines. These
results highlight the promise of integrating stepwise process feedback into LLM
training, paving the way toward more interpretable and dependable reasoning
capabilities.
