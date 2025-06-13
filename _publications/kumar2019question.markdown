---
layout: publication
title: 'Question Generation From Paragraphs: A Tale Of Two Hierarchical Models'
authors: Vishwajeet Kumar, Raktim Chaki, Sai Teja Talluri, Ganesh Ramakrishnan, Yuan-fang Li, Gholamreza Haffari
conference: "Arxiv"
year: 2019
bibkey: kumar2019question
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1911.03407'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Automatic question generation from paragraphs is an important and challenging
problem, particularly due to the long context from paragraphs. In this paper,
we propose and study two hierarchical models for the task of question
generation from paragraphs. Specifically, we propose (a) a novel hierarchical
BiLSTM model with selective attention and (b) a novel hierarchical Transformer
architecture, both of which learn hierarchical representations of paragraphs.
We model a paragraph in terms of its constituent sentences, and a sentence in
terms of its constituent words. While the introduction of the attention
mechanism benefits the hierarchical BiLSTM model, the hierarchical Transformer,
with its inherent attention and positional encoding mechanisms also performs
better than flat transformer model. We conducted empirical evaluation on the
widely used SQuAD and MS MARCO datasets using standard metrics. The results
demonstrate the overall effectiveness of the hierarchical models over their
flat counterparts. Qualitatively, our hierarchical models are able to generate
fluent and relevant questions
