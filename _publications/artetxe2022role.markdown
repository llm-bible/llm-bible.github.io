---
layout: publication
title: 'On The Role Of Bidirectionality In Language Model Pre-training'
authors: Mikel Artetxe, Jingfei Du, Naman Goyal, Luke Zettlemoyer, Ves Stoyanov
conference: "Arxiv"
year: 2022
bibkey: artetxe2022role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11726"}
tags: ['Training Techniques', 'Model Architecture', 'Survey Paper', 'Tools', 'Language Modeling', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Pre-Training', 'Attention Mechanism']
---
Prior work on language model pre-training has explored different
architectures and learning objectives, but differences in data, hyperparameters
and evaluation make a principled comparison difficult. In this work, we focus
on bidirectionality as a key factor that differentiates existing approaches,
and present a comprehensive study of its role in next token prediction, text
infilling, zero-shot priming and fine-tuning. We propose a new framework that
generalizes prior approaches, including fully unidirectional models like GPT,
fully bidirectional models like BERT, and hybrid models like CM3 and prefix LM.
Our framework distinguishes between two notions of bidirectionality
(bidirectional context and bidirectional attention) and allows us to control
each of them separately. We find that the optimal configuration is largely
application-dependent (e.g., bidirectional attention is beneficial for
fine-tuning and infilling, but harmful for next token prediction and zero-shot
priming). We train models with up to 6.7B parameters, and find differences to
remain consistent at scale. While prior work on scaling has focused on
left-to-right autoregressive models, our results suggest that this approach
comes with some trade-offs, and it might be worthwhile to develop very large
bidirectional models.
