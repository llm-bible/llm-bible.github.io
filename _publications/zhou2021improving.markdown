---
layout: publication
title: "Improving Sequence-to-sequence Pre-training Via Sequence Span Rewriting"
authors: Zhou Wangchunshu, Ge Tao, Xu Canwen, Xu Ke, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: zhou2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.00416"}
tags: ['BERT', 'Masked Language Model', 'Pretraining Methods', 'Training Techniques']
---
In this paper we generalize text infilling (e.g. masked language models) by proposing Sequence Span Rewriting (SSR) as a self-supervised sequence-to-sequence (seq2seq) pre-training objective. SSR provides more fine-grained learning signals for text representations by supervising the model to rewrite imperfect spans to ground truth and it is more consistent than text infilling with many downstream seq2seq tasks that rewrite a source sentences into a target sentence. Our experiments with T5 models on various seq2seq tasks show that SSR can substantially improve seq2seq pre-training. Moreover we observe SSR is especially helpful to improve pre-training a small-size seq2seq model with a powerful imperfect span generator which indicates a new perspective of transferring knowledge from a large model to a smaller model for seq2seq pre-training.
