---
layout: publication
title: Extrapolating Multilingual Understanding Models As Multilingual Generators
authors: Wu Bohong, Yuan Fei, Zhao Hai, Li Lei, Xu Jingjing
conference: "Arxiv"
year: 2023
bibkey: wu2023extrapolating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13140"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods']
---
Multilingual understanding models (or encoder45;based) pre45;trained via masked language modeling have achieved promising results on many language understanding tasks (e.g. mBERT). However these non45;autoregressive (NAR) models still struggle to generate high45;quality texts compared with autoregressive (AR) models. Considering that encoder45;based models have the advantage of efficient generation and self45;correction abilities this paper explores methods to empower multilingual understanding models the generation abilities to get a unified model. Specifically we start from a multilingual encoder (XLM45;R) and propose a textbf123;S125;emantic45;textbf123;G125;uided textbf123;A125;lignment45;then45;Denoising (SGA) approach to adapt an encoder to a multilingual generator with a small number of new parameters. Experiments show that the proposed approach is an effective adaption method outperforming widely45;used initialization45;based methods with gains of 9.4 BLEU on machine translation 8.1 Rouge45;L on question generation and 5.5 METEOR on story generation on XLM45;R95;123;large125;. On the other hand we observe that XLM45;R is still inferior to mBART in supervised settings despite better results on zero45;shot settings indicating that more exploration is required to make understanding models strong generators.
