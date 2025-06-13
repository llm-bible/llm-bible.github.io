---
layout: publication
title: 'Seamless Language Expansion: Enhancing Multilingual Mastery In Self-supervised Models'
authors: Jing Xu, Minglin Wu, Xixin Wu, Helen Meng
conference: "Arxiv"
year: 2024
bibkey: xu2024seamless
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14092'}
tags: ['Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning']
---
Self-supervised (SSL) models have shown great performance in various
downstream tasks. However, they are typically developed for limited languages,
and may encounter new languages in real-world. Developing a SSL model for each
new language is costly. Thus, it is vital to figure out how to efficiently
adapt existed SSL models to a new language without impairing its original
abilities. We propose adaptation methods which integrate LoRA to existed SSL
models to extend new language. We also develop preservation strategies which
include data combination and re-clustering to retain abilities on existed
languages. Applied to mHuBERT, we investigate their effectiveness on speech
re-synthesis task. Experiments show that our adaptation methods enable mHuBERT
to be applied to a new language (Mandarin) with MOS value increased about 1.6
and the relative value of WER reduced up to 61.72%. Also, our preservation
strategies ensure that the performance on both existed and new languages
remains intact.
