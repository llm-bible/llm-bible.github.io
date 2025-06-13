---
layout: publication
title: 'Revisiting Large Language Model Pruning Using Neuron Semantic Attribution'
authors: Yizhuo Ding, Xinwei Sun, Yanwei Fu, Guosheng Hu
conference: "Arxiv"
year: 2025
bibkey: ding2025revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01542"}
tags: ['Efficiency and Optimization', 'Pruning']
---
Model pruning technique is vital for accelerating large language models by
reducing their size and computational requirements. However, the
generalizability of existing pruning methods across diverse datasets and tasks
remains unclear. Thus, we conduct extensive evaluations on 24 datasets and 4
tasks using popular pruning methods. Based on these evaluations, we find and
then investigate that calibration set greatly affect the performance of pruning
methods. In addition, we surprisingly find a significant performance drop of
existing pruning methods in sentiment classification tasks. To understand the
link between performance drop and pruned neurons, we propose Neuron Semantic
Attribution, which learns to associate each neuron with specific semantics.
This method first makes the unpruned neurons of LLMs explainable.
