---
layout: publication
title: Universal Sentence Encoder
authors: Daniel Cer et al.
conference: Arxiv
year: 2018
citations: 1362
bibkey: cer2018universal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.11175'}]
tags: [Fine-Tuning, Ethics and Bias]
---
We present models for encoding sentences into embedding vectors that
specifically target transfer learning to other NLP tasks. The models are
efficient and result in accurate performance on diverse transfer tasks. Two
variants of the encoding models allow for trade-offs between accuracy and
compute resources. For both variants, we investigate and report the
relationship between model complexity, resource consumption, the availability
of transfer task training data, and task performance. Comparisons are made with
baselines that use word level transfer learning via pretrained word embeddings
as well as baselines do not use any transfer learning. We find that transfer
learning using sentence embeddings tends to outperform word level transfer.
With transfer learning via sentence embeddings, we observe surprisingly good
performance with minimal amounts of supervised training data for a transfer
task. We obtain encouraging results on Word Embedding Association Tests (WEAT)
targeted at detecting model bias. Our pre-trained sentence encoding models are
made freely available for download and on TF Hub.