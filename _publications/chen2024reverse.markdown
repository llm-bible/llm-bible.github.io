---
layout: publication
title: 'Reverse Thinking Makes Llms Stronger Reasoners'
authors: Justin Chih-yao Chen, Zifeng Wang, Hamid Palangi, Rujun Han, Sayna Ebrahimi, Long Le, Vincent Perot, Swaroop Mishra, Mohit Bansal, Chen-yu Lee, Tomas Pfister
conference: "Arxiv"
year: 2024
bibkey: chen2024reverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19865"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Reverse thinking plays a crucial role in human reasoning. Humans can reason
not only from a problem to a solution but also in reverse, i.e., start from the
solution and reason towards the problem. This often enhances overall reasoning
performance as it enables consistency checks between their forward and backward
thinking. To enable Large Language Models (LLMs) to perform reverse thinking,
we introduce Reverse-Enhanced Thinking (RevThink), a framework composed of data
augmentation and learning objectives. In RevThink, we augment the dataset by
collecting structured forward-backward reasoning from a teacher model,
consisting of: (1) the original question, (2) forward reasoning, (3) backward
question, and (4) backward reasoning. We then employ three objectives to train
a smaller student model in a multi-task learning fashion: (a) generate forward
reasoning from a question, (b) generate a backward question from a question,
and (c) generate backward reasoning from the backward question. Experiments
across 12 datasets covering commonsense, math, and logical reasoning show an
average 13.53% improvement over the student model's zero-shot performance and a
6.84% improvement over the strongest knowledge distillation baselines.
Moreover, our method demonstrates sample efficiency -- using only 10% of the
correct forward reasoning from the training data, it outperforms a standard
fine-tuning method trained on 10x more forward reasoning. RevThink also
exhibits strong generalization to out-of-distribution held-out datasets.
