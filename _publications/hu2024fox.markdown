---
layout: publication
title: 'Fox-1: Open Small Language Model For Cloud And Edge'
authors: Zijian Hu, Jipeng Zhang, Rui Pan, Zhaozhuo Xu, Shanshan Han, Han Jin, Alay Dilipbhai Shah, Dimitris Stripelis, Yuhang Yao, Salman Avestimehr, Tong Zhang, Chaoyang He
conference: "Arxiv"
year: 2024
bibkey: hu2024fox
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05281'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pre-Training']
---
We present Fox-1, a series of small language models (SLMs) consisting of
Fox-1-1.6B and Fox-1-1.6B-Instruct-v0.1. These models are pre-trained on 3
trillion tokens of web-scraped document data and fine-tuned with 5 billion
tokens of instruction-following and multi-turn conversation data. Aiming to
improve the pre-training efficiency, Fox-1-1.6B model introduces a novel
3-stage data curriculum across all the training data with 2K-8K sequence
length. In architecture design, Fox-1 features a deeper layer structure, an
expanded vocabulary, and utilizes Grouped Query Attention (GQA), offering a
performant and efficient architecture compared to other SLMs. Fox-1 achieves
better or on-par performance in various benchmarks compared to StableLM-2-1.6B,
Gemma-2B, Qwen1.5-1.8B, and OpenELM1.1B, with competitive inference speed and
throughput. The model weights have been released under the Apache 2.0 license,
where we aim to promote the democratization of LLMs and make them fully
accessible to the whole open-source community.
