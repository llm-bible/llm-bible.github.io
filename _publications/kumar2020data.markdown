---
layout: publication
title: Data Augmentation Using Pre-trained Transformer Models
authors: Varun Kumar, Ashutosh Choudhary, Eunah Cho
conference: Arxiv
year: 2020
citations: 35
bibkey: kumar2020data
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.02245'}]
tags: [GPT, Transformer, BERT]
---
Language model based pre-trained models such as BERT have provided
significant gains across different NLP tasks. In this paper, we study different
types of transformer based pre-trained models such as auto-regressive models
(GPT-2), auto-encoder models (BERT), and seq2seq models (BART) for conditional
data augmentation. We show that prepending the class labels to text sequences
provides a simple yet effective way to condition the pre-trained models for
data augmentation. Additionally, on three classification benchmarks,
pre-trained Seq2Seq model outperforms other data augmentation methods in a
low-resource setting. Further, we explore how different pre-trained model based
data augmentation differs in-terms of data diversity, and how well such methods
preserve the class-label information.