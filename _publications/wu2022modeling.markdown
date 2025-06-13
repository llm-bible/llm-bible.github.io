---
layout: publication
title: 'Modeling Context With Linear Attention For Scalable Document-level Translation'
authors: Zhaofeng Wu, Hao Peng, Nikolaos Pappas, Noah A. Smith
conference: "Arxiv"
year: 2022
bibkey: wu2022modeling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.08431'}
tags: ['Attention Mechanism', 'Transformer', 'SLT', 'RAG', 'Model Architecture', 'Applications', 'Ethics and Bias', 'Pretraining Methods']
---
Document-level machine translation leverages inter-sentence dependencies to
produce more coherent and consistent translations. However, these models,
predominantly based on transformers, are difficult to scale to long documents
as their attention layers have quadratic complexity in the sequence length.
Recent efforts on efficient attention improve scalability, but their effect on
document translation remains unexplored. In this work, we investigate the
efficacy of a recent linear attention model by Peng et al. (2021) on document
translation and augment it with a sentential gate to promote a recency
inductive bias. We evaluate the model on IWSLT 2015 and OpenSubtitles 2018
against the transformer, demonstrating substantially increased decoding speed
on long sequences with similar or better BLEU scores. We show that sentential
gating further improves translation quality on IWSLT.
