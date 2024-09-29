---
layout: publication
title: Unilmv2 Pseudo45;masked Language Models For Unified Language Model Pre45;training
authors: Bao Hangbo, Dong Li, Wei Furu, Wang Wenhui, Yang Nan, Liu Xiaodong, Wang Yu, Piao Songhao, Gao Jianfeng, Zhou Ming, Hon Hsiao-wuen
conference: "Arxiv"
year: 2020
bibkey: bao2020pseudo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.12804"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'GPT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We propose to pre45;train a unified language model for both autoencoding and partially autoregressive language modeling tasks using a novel training procedure referred to as a pseudo45;masked language model (PMLM). Given an input text with masked tokens we rely on conventional masks to learn inter45;relations between corrupted tokens and context via autoencoding and pseudo masks to learn intra45;relations between masked spans via partially autoregressive modeling. With well45;designed position embeddings and self45;attention masks the context encodings are reused to avoid redundant computation. Moreover conventional masks used for autoencoding provide global masking information so that all the position embeddings are accessible in partially autoregressive language modeling. In addition the two tasks pre45;train a unified language model as a bidirectional encoder and a sequence45;to45;sequence decoder respectively. Our experiments show that the unified language models pre45;trained using PMLM achieve new state45;of45;the45;art results on a wide range of natural language understanding and generation tasks across several widely used benchmarks.
