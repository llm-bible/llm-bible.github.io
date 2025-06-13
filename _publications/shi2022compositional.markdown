---
layout: publication
title: 'Compositional Generalization And Decomposition In Neural Program Synthesis'
authors: Kensen Shi, Joey Hong, Manzil Zaheer, Pengcheng Yin, Charles Sutton
conference: "Arxiv"
year: 2022
bibkey: shi2022compositional
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.03758'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
When writing programs, people have the ability to tackle a new complex task
by decomposing it into smaller and more familiar subtasks. While it is
difficult to measure whether neural program synthesis methods have similar
capabilities, what we can measure is whether they compositionally generalize,
that is, whether a model that has been trained on the simpler subtasks is
subsequently able to solve more complex tasks. In this paper, we focus on
measuring the ability of learned program synthesizers to compositionally
generalize. We first characterize several different axes along which program
synthesis methods would be desired to generalize, e.g., length generalization,
or the ability to combine known subroutines in new ways that do not occur in
the training data. Based on this characterization, we introduce a benchmark
suite of tasks to assess these abilities based on two popular existing
datasets, SCAN and RobustFill. Finally, we make first attempts to improve the
compositional generalization ability of Transformer models along these axes
through novel attention mechanisms that draw inspiration from a human-like
decomposition strategy. Empirically, we find our modified Transformer models
generally perform better than natural baselines, but the tasks remain
challenging.
