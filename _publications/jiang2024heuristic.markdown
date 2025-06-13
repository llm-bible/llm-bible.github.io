---
layout: publication
title: 'Heuristic-enhanced Candidates Selection Strategy For Gpts Tackle Few-shot Aspect-based Sentiment Analysis'
authors: Baoxing Jiang, Yujie Wan, Shenggen Ju
conference: "Arxiv"
year: 2024
bibkey: jiang2024heuristic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06063"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Few-Shot']
---
Few-Shot Aspect-Based Sentiment Analysis (FSABSA) is an indispensable and
highly challenging task in natural language processing. However, methods based
on Pre-trained Language Models (PLMs) struggle to accommodate multiple
sub-tasks, and methods based on Generative Pre-trained Transformers (GPTs)
perform poorly. To address the above issues, the paper designs a
Heuristic-enhanced Candidates Selection (HCS) strategy and further proposes All
in One (AiO) model based on it. The model works in a two-stage, which
simultaneously accommodates the accuracy of PLMs and the generalization
capability of GPTs. Specifically, in the first stage, a backbone model based on
PLMs generates rough heuristic candidates for the input sentence. In the second
stage, AiO leverages LLMs' contextual learning capabilities to generate precise
predictions. The study conducted comprehensive comparative and ablation
experiments on five benchmark datasets. The experimental results demonstrate
that the proposed model can better adapt to multiple sub-tasks, and also
outperforms the methods that directly utilize GPTs.
