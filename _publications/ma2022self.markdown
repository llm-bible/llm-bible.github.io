---
layout: publication
title: 'Self-eval: Self-supervised Fine-grained Dialogue Evaluation'
authors: Longxuan Ma, Ziyu Zhuang, Weinan Zhang, Mingda Li, Ting Liu
conference: "Arxiv"
year: 2022
bibkey: ma2022self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08094"}
tags: ['Pretraining Methods', 'Training Techniques', 'Tools']
---
This paper introduces a novel Self-supervised Fine-grained Dialogue
Evaluation framework (SelF-Eval). The core idea is to model the correlation
between turn quality and the entire dialogue quality. We first propose a novel
automatic data construction method that can automatically assign fine-grained
scores for arbitrarily dialogue data. Then we train \textbf\{SelF-Eval\} with a
multi-level contrastive learning schema which helps to distinguish different
score levels. Experimental results on multiple benchmarks show that SelF-Eval
is highly consistent with human evaluations and better than the
state-of-the-art models. We give a detailed analysis of the experiments in this
paper. Our code is available on GitHub.
