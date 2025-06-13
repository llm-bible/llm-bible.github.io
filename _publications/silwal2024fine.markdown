---
layout: publication
title: 'Fine-tuning Small Embeddings For Elevated Performance'
authors: Biraj Silwal
conference: "Arxiv"
year: 2024
bibkey: silwal2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18099"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'ACL', 'Attention Mechanism']
---
Contextual Embeddings have yielded state-of-the-art results in various
natural language processing tasks. However, these embeddings are constrained by
models requiring large amounts of data and huge computing power. This is an
issue for low-resource languages like Nepali as the amount of data available
over the internet is not always sufficient for the models. This work has taken
an incomplete BERT model with six attention heads pretrained on Nepali language
and finetuned it on previously unseen data. The obtained results from intrinsic
and extrinsic evaluations have been compared to the results drawn from the
original model baseline and a complete BERT model pretrained on Nepali language
as the oracle. The results demonstrate that even though the oracle is better on
average, finetuning the small embeddings drastically improves results compared
to the original baseline.
