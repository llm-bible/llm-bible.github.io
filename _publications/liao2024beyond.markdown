---
layout: publication
title: Beyond KV Caching: Shared Attention For Efficient Llms
authors: Liao Bingli, Vargas Danilo Vasconcellos
conference: "Arxiv"
year: 2024
bibkey: liao2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12866"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The efficiency of large language models (LLMs) remains a critical challenge particularly in contexts where computational resources are limited. Traditional attention mechanisms in these models while powerful require significant computational and memory resources due to the necessity of recalculating and storing attention weights across different layers. This paper introduces a novel Shared Attention (SA) mechanism designed to enhance the efficiency of LLMs by directly sharing computed attention weights across multiple layers. Unlike previous methods that focus on sharing intermediate Key-Value (KV) caches our approach utilizes the isotropic tendencies of attention distributions observed in advanced LLMs post-pretraining to reduce both the computational flops and the size of the KV cache required during inference. We empirically demonstrate that implementing SA across various LLMs results in minimal accuracy loss on standard benchmarks. Our findings suggest that SA not only conserves computational resources but also maintains robust model performance thereby facilitating the deployment of more efficient LLMs in resource-constrained environments.
