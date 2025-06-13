---
layout: publication
title: 'Compress, Gather, And Recompute: Reforming Long-context Processing In Transformers'
authors: Woomin Song, Sai Muralidhar Jayanthi, Srikanth Ronanki, Kanthashree Mysore Sathyendra, Jinwoo Shin, Aram Galstyan, Shubham Katiyar, Sravan Babu Bodapati
conference: "Arxiv"
year: 2025
bibkey: song2025reforming
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01215'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
As large language models increasingly gain popularity in real-world applications, processing extremely long contexts, often exceeding the model's pre-trained context limits, has emerged as a critical challenge. While existing approaches to efficient long-context processing show promise, recurrent compression-based methods struggle with information preservation, whereas random access approaches require substantial memory resources. We introduce REFORM, a novel inference framework that efficiently handles long contexts through a two-phase approach. First, it incrementally processes input chunks while maintaining a compressed KV cache, constructs cross-layer context embeddings, and utilizes early exit strategy for improved efficiency. Second, it identifies and gathers essential tokens via similarity matching and selectively recomputes the KV cache. Compared to baselines, REFORM achieves over 50% and 27% performance gains on RULER and BABILong respectively at 1M context length. It also outperforms baselines on Infinite-Bench and MM-NIAH, demonstrating flexibility across diverse tasks and domains. Additionally, REFORM reduces inference time by 30% and peak memory usage by 5%, achieving both efficiency and superior performance.
