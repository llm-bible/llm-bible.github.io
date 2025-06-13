---
layout: publication
title: 'Reasoning Path Compression: Compressing Generation Trajectories For Efficient LLM Reasoning'
authors: Jiwon Song, Dongwon Jo, Yulhwa Kim, Jae-joon Kim
conference: "Arxiv"
year: 2025
bibkey: song2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13866"}
  - {name: "Code", url: "https://github.com/jiwonsong-dev/ReasoningPathCompression"}
tags: ['RAG', 'Training Techniques', 'Has Code']
---
Recent reasoning-focused language models achieve high accuracy by generating lengthy intermediate reasoning paths before producing final answers. While this approach is effective in solving problems that require logical thinking, long reasoning paths significantly increase memory usage and throughput of token generation, limiting the practical deployment of such models. We propose Reasoning Path Compression (RPC), a training-free method that accelerates inference by leveraging the semantic sparsity of reasoning paths. RPC periodically compresses the KV cache by retaining KV cache that receive high importance score, which are computed using a selector window composed of recently generated queries. Experiments show that RPC improves generation throughput of QwQ-32B by up to 1.60\\(\times\\) compared to the inference with full KV cache, with an accuracy drop of 1.2% on the AIME 2024 benchmark. Our findings demonstrate that semantic sparsity in reasoning traces can be effectively exploited for compression, offering a practical path toward efficient deployment of reasoning LLMs. Our code is available at https://github.com/jiwonsong-dev/ReasoningPathCompression.
