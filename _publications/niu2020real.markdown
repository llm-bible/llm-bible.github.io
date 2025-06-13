---
layout: publication
title: 'Real-time Execution Of Large-scale Language Models On Mobile'
authors: Wei Niu, Zhenglun Kong, Geng Yuan, Weiwen Jiang, Jiexiong Guan, Caiwen Ding, Pu Zhao, Sijia Liu, Bin Ren, Yanzhi Wang
conference: "Arxiv"
year: 2020
bibkey: niu2020real
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2009.06823'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'BERT', 'Pretraining Methods']
---
Pre-trained large-scale language models have increasingly demonstrated high
accuracy on many natural language processing (NLP) tasks. However, the limited
weight storage and computational speed on hardware platforms have impeded the
popularity of pre-trained models, especially in the era of edge computing. In
this paper, we seek to find the best model structure of BERT for a given
computation size to match specific devices. We propose the first compiler-aware
neural architecture optimization framework. Our framework can guarantee the
identified model to meet both resource and real-time specifications of mobile
devices, thus achieving real-time execution of large transformer-based models
like BERT variants. We evaluate our model on several NLP tasks, achieving
competitive results on well-known benchmarks with lower latency on mobile
devices. Specifically, our model is 5.2x faster on CPU and 4.1x faster on GPU
with 0.5-2% accuracy loss compared with BERT-base. Our overall framework
achieves up to 7.8x speedup compared with TensorFlow-Lite with only minor
accuracy loss.
