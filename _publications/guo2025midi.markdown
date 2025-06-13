---
layout: publication
title: 'Moonbeam: A MIDI Foundation Model Using Both Absolute And Relative Music Attributes'
authors: Zixun Guo, Simon Dixon
conference: "Arxiv"
year: 2025
bibkey: guo2025midi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15559"}
tags: ['Model Architecture', 'Tokenization', 'RAG', 'Pretraining Methods', 'Ethics and Bias', 'Transformer', 'Attention Mechanism']
---
Moonbeam is a transformer-based foundation model for symbolic music, pretrained on a large and diverse collection of MIDI data totaling 81.6K hours of music and 18 billion tokens. Moonbeam incorporates music-domain inductive biases by capturing both absolute and relative musical attributes through the introduction of a novel domain-knowledge-inspired tokenization method and Multidimensional Relative Attention (MRA), which captures relative music information without additional trainable parameters. Leveraging the pretrained Moonbeam, we propose 2 finetuning architectures with full anticipatory capabilities, targeting 2 categories of downstream tasks: symbolic music understanding and conditional music generation (including music infilling). Our model outperforms other large-scale pretrained music models in most cases in terms of accuracy and F1 score across 3 downstream music classification tasks on 4 datasets. Moreover, our finetuned conditional music generation model outperforms a strong transformer baseline with a REMI-like tokenizer. We open-source the code, pretrained model, and generated samples on Github.
