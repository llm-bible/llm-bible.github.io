---
layout: publication
title: 'Generic Token Compression In Multimodal Large Language Models From An Explainability Perspective'
authors: Lei Lei, Jie Gu, Xiaokang Ma, Chu Tang, Jingmin Chen, Tong Xu
conference: "Arxiv"
year: 2025
bibkey: lei2025generic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01097'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Multimodal Models', 'Interpretability']
---
Existing Multimodal Large Language Models (MLLMs) process a large number of visual tokens, leading to significant computational costs and inefficiency. Previous works generally assume that all visual tokens are necessary in the shallow layers of LLMs, and therefore token compression typically occurs in intermediate layers. In contrast, our study reveals an interesting insight: with proper selection, token compression is feasible at the input stage of LLM with negligible performance loss. Specifically, we reveal that explainability methods can effectively evaluate the importance of each visual token with respect to the given instruction, which can well guide the token compression. Furthermore, we propose to learn a mapping from the attention map of the first LLM layer to the explanation results, thereby avoiding the need for a full inference pass and facilitating practical deployment. Interestingly, this mapping can be learned using a simple and lightweight convolutional network, whose training is efficient and independent of MLLMs. Extensive experiments on 10 image and video benchmarks across three leading MLLMs (Qwen2-VL, LLaVA-OneVision, and VILA1.5) demonstrate the effectiveness of our approach, e.g., pruning 50% visual tokens while retaining more than 96% of the original performance across all benchmarks for all these three MLLMs. It also exhibits strong generalization, even when the number of tokens in inference far exceeds that used in training.
