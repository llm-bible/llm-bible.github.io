---
layout: publication
title: 'Transformer: Slow-fast Transformer For Machine Translation'
authors: Bei Li, Yi Jing, Xu Tan, Zhen Xing, Tong Xiao, Jingbo Zhu
conference: "Arxiv"
year: 2023
bibkey: li2023slow
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16982"}
tags: ['Applications', 'Pretraining Methods', 'Model Architecture', 'Transformer']
---
Learning multiscale Transformer models has been evidenced as a viable
approach to augmenting machine translation systems. Prior research has
primarily focused on treating subwords as basic units in developing such
systems. However, the incorporation of fine-grained character-level features
into multiscale Transformer has not yet been explored. In this work, we present
a \textbf\{S\}low-\textbf\{F\}ast two-stream learning model, referred to as
Tran\textbf\{SF\}ormer, which utilizes a ``slow'' branch to deal with subword
sequences and a ``fast'' branch to deal with longer character sequences. This
model is efficient since the fast branch is very lightweight by reducing the
model width, and yet provides useful fine-grained features for the slow branch.
Our TranSFormer shows consistent BLEU improvements (larger than 1 BLEU point)
on several machine translation benchmarks.
