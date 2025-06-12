---
layout: publication
title: 'Simple Recurrent Units For Highly Parallelizable Recurrence'
authors: Lei Tao, Zhang Yu, Wang Sida I., Dai Hui, Artzi Yoav
conference: "Arxiv"
year: 2017
citations: 244
bibkey: lei2017simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1709.02755"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'RAG', 'Applications', 'Reinforcement Learning']
---
Common recurrent neural architectures scale poorly due to the intrinsic
difficulty in parallelizing their state computations. In this work, we propose
the Simple Recurrent Unit (SRU), a light recurrent unit that balances model
capacity and scalability. SRU is designed to provide expressive recurrence,
enable highly parallelized implementation, and comes with careful
initialization to facilitate training of deep models. We demonstrate the
effectiveness of SRU on multiple NLP tasks. SRU achieves 5--9x speed-up over
cuDNN-optimized LSTM on classification and question answering datasets, and
delivers stronger results than LSTM and convolutional models. We also obtain an
average of 0.7 BLEU improvement over the Transformer model on translation by
incorporating SRU into the architecture.
