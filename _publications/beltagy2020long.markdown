---
layout: publication
title: Longformer The Long45;document Transformer
authors: Beltagy Iz, Peters Matthew E., Cohan Arman
conference: "Arxiv"
year: 2020
bibkey: beltagy2020long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.05150"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Transformer45;based models are unable to process long sequences due to their self45;attention operation which scales quadratically with the sequence length. To address this limitation we introduce the Longformer with an attention mechanism that scales linearly with sequence length making it easy to process documents of thousands of tokens or longer. Longformers attention mechanism is a drop45;in replacement for the standard self45;attention and combines a local windowed attention with a task motivated global attention. Following prior work on long45;sequence transformers we evaluate Longformer on character45;level language modeling and achieve state45;of45;the45;art results on text8 and enwik8. In contrast to most prior work we also pretrain Longformer and finetune it on a variety of downstream tasks. Our pretrained Longformer consistently outperforms RoBERTa on long document tasks and sets new state45;of45;the45;art results on WikiHop and TriviaQA. We finally introduce the Longformer45;Encoder45;Decoder (LED) a Longformer variant for supporting long document generative sequence45;to45;sequence tasks and demonstrate its effectiveness on the arXiv summarization dataset.
