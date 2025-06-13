---
layout: publication
title: 'LLM As Effective Streaming Processor: Bridging Streaming-batch Mismatches With Group Position Encoding'
authors: Junlong Tong, Jinlan Fu, Zixuan Lin, Yingqi Fan, Anhao Zhao, Hui Su, Xiaoyu Shen
conference: "Arxiv"
year: 2025
bibkey: tong2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16983'}
  - {name: "Code", url: 'https://github.com/EIT-NLP/StreamingLLM'}
tags: ['Attention Mechanism', 'Has Code', 'Multimodal Models', 'Model Architecture']
---
Large Language Models (LLMs) are primarily designed for batch processing. Existing methods for adapting LLMs to streaming rely either on expensive re-encoding or specialized architectures with limited scalability. This work identifies three key mismatches in adapting batch-oriented LLMs to streaming: (1) input-attention, (2) output-attention, and (3) position-ID mismatches. While it is commonly assumed that the latter two mismatches require frequent re-encoding, our analysis reveals that only the input-attention mismatch significantly impacts performance, indicating re-encoding outputs is largely unnecessary. To better understand this discrepancy with the common assumption, we provide the first comprehensive analysis of the impact of position encoding on LLMs in streaming, showing that preserving relative positions within source and target contexts is more critical than maintaining absolute order. Motivated by the above analysis, we introduce a group position encoding paradigm built on batch architectures to enhance consistency between streaming and batch modes. Extensive experiments on cross-lingual and cross-modal tasks demonstrate that our method outperforms existing approaches. Our method requires no architectural modifications, exhibits strong generalization in both streaming and batch modes. The code is available at repository https://github.com/EIT-NLP/StreamingLLM.
