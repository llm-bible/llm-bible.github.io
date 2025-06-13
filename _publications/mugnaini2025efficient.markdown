---
layout: publication
title: 'Efficient Llms With AMP: Attention Heads And MLP Pruning'
authors: Leandro Giusti Mugnaini, Bruno Lopes Yamamoto, Lucas Lauton De Alcantara, Victor Zacarias, Edson Bollis, Lucas Pellicer, Anna Helena Reali Costa, Artur Jordao
conference: "Arxiv"
year: 2025
bibkey: mugnaini2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21174"}
tags: ['Efficiency and Optimization', 'Attention Mechanism', 'Pruning', 'Model Architecture']
---
Deep learning drives a new wave in computing systems and triggers the
automation of increasingly complex problems. In particular, Large Language
Models (LLMs) have significantly advanced cognitive tasks, often matching or
even surpassing human-level performance. However, their extensive parameters
result in high computational costs and slow inference, posing challenges for
deployment in resource-limited settings. Among the strategies to overcome the
aforementioned challenges, pruning emerges as a successful mechanism since it
reduces model size while maintaining predictive ability. In this paper, we
introduce AMP: Attention Heads and MLP Pruning, a novel structured pruning
method that efficiently compresses LLMs by removing less critical structures
within Multi-Head Attention (MHA) and Multilayer Perceptron (MLP). By
projecting the input data onto weights, AMP assesses structural importance and
overcomes the limitations of existing techniques, which often fall short in
flexibility or efficiency. In particular, AMP surpasses the current
state-of-the-art on commonsense reasoning tasks by up to 1.49 percentage
points, achieving a 30% pruning ratio with minimal impact on zero-shot task
performance. Moreover, AMP also improves inference speeds, making it
well-suited for deployment in resource-constrained environments. We confirm the
flexibility of AMP on different families of LLMs, including LLaMA and Phi.
