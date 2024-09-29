---
layout: publication
title: MLKV Multi45;layer Key45;value Heads For Memory Efficient Transformer Decoding
authors: Zuhri Zayd Muhammad Kawakibi, Adilazuarda Muhammad Farid, Purwarianti Ayu, Aji Alham Fikri
conference: "Arxiv"
year: 2024
bibkey: zuhri2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09297"}
  - {name: "Code", url: "https://github.com/zaydzuhri/pythia&#45;mlkv"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Auto45;regressive inference of transformers benefit greatly from Key45;Value (KV) caching but can lead to major memory bottlenecks as model size batch size and sequence length grow at scale. We introduce Multi45;Layer Key45;Value (MLKV) sharing a novel approach extending KV sharing across transformer layers to reduce memory usage beyond what was possible with Multi45;Query Attention (MQA) and Grouped45;Query Attention (GQA). Evaluations on various NLP benchmarks and inference metrics using uptrained Pythia45;160M variants demonstrate that MLKV significantly reduces memory usage with minimal performance loss reducing KV cache size down to a factor of 6x compared to MQA. These results highlight MLKVs potential for efficient deployment of transformer models at scale. We provide code at https://github.com/zaydzuhri/pythia&#45;mlkv
