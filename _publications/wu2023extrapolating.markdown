---
layout: publication
title: 'Extrapolating Multilingual Understanding Models As Multilingual Generators'
authors: Wu Bohong, Yuan Fei, Zhao Hai, Li Lei, Xu Jingjing
conference: "Arxiv"
year: 2023
bibkey: wu2023extrapolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13140"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods']
---
Multilingual understanding models (or encoder-based) pre-trained via masked language modeling have achieved promising results on many language understanding tasks (e.g. mBERT). However these non-autoregressive (NAR) models still struggle to generate high-quality texts compared with autoregressive (AR) models. Considering that encoder-based models have the advantage of efficient generation and self-correction abilities this paper explores methods to empower multilingual understanding models the generation abilities to get a unified model. Specifically we start from a multilingual encoder (XLM-R) and propose a textbfSemantic-textbfGuided textbfAlignment-then-Denoising (SGA) approach to adapt an encoder to a multilingual generator with a small number of new parameters. Experiments show that the proposed approach is an effective adaption method outperforming widely-used initialization-based methods with gains of 9.4 BLEU on machine translation 8.1 Rouge-L on question generation and 5.5 METEOR on story generation on XLM-R(_large). On the other hand we observe that XLM-R is still inferior to mBART in supervised settings despite better results on zero-shot settings indicating that more exploration is required to make understanding models strong generators.
