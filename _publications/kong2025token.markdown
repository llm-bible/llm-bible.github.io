---
layout: publication
title: 'Token Reduction Should Go Beyond Efficiency In Generative Models -- From Vision, Language To Multimodality'
authors: Zhenglun Kong, Yize Li, Fanhu Zeng, Lei Xin, Shvat Messica, Xue Lin, Pu Zhao, Manolis Kellis, Hao Tang, Marinka Zitnik
conference: "Arxiv"
year: 2025
bibkey: kong2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18227"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Efficiency and Optimization', 'Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Prompting', 'Applications', 'Attention Mechanism']
---
In Transformer architectures, tokens\textemdash discrete units derived from raw data\textemdash are formed by segmenting inputs into fixed-length chunks. Each token is then mapped to an embedding, enabling parallel attention computations while preserving the input's essential information. Due to the quadratic computational complexity of transformer self-attention mechanisms, token reduction has primarily been used as an efficiency strategy. This is especially true in single vision and language domains, where it helps balance computational costs, memory usage, and inference latency. Despite these advances, this paper argues that token reduction should transcend its traditional efficiency-oriented role in the era of large generative models. Instead, we position it as a fundamental principle in generative modeling, critically influencing both model architecture and broader applications. Specifically, we contend that across vision, language, and multimodal systems, token reduction can: (i) facilitate deeper multimodal integration and alignment, (ii) mitigate "overthinking" and hallucinations, (iii) maintain coherence over long inputs, and (iv) enhance training stability, etc. We reframe token reduction as more than an efficiency measure. By doing so, we outline promising future directions, including algorithm design, reinforcement learning-guided token reduction, token optimization for in-context learning, and broader ML and scientific domains. We highlight its potential to drive new model architectures and learning strategies that improve robustness, increase interpretability, and better align with the objectives of generative modeling.
