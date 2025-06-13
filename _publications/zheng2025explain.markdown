---
layout: publication
title: 'Explain What You Mean: Intent Augmented Knowledge Graph Recommender Built With An LLM'
authors: Wenqing Zheng, Noah Fatsi, Daniel Barcklow, Dmitri Kalaev, Steven Yao, Owen Reinert, C. Bayan Bruss, Daniele Rosa
conference: "Arxiv"
year: 2025
bibkey: zheng2025explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10900"}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Interaction sparsity is a long-standing challenge in recommendation systems. Sparsity manifests in environments with disproportional cardinality of groupings of entities, such as users and products in an online marketplace. It is also found for newly introduced entities, described as the cold-start problem. Recent efforts to mitigate this issue either enrich the connectivity data by incorporating social networks or external knowledge graphs, or fine-tune LLMs into interaction augmenters or next-item recommenders. However, these techniques tend to be resource demanding, requiring high computational power. They also have several limitations, including data availability, low quality, or synthetic noise issues. In this work, we propose LLM-based Intent Knowledge Graph Recommender (IKGR), a novel framework that leverages retrieval-augmented generation and an encoding approach to construct and densify a knowledge graph. IKGR leverages latent user-item affinities from an interaction knowledge graph and further densifies it through mutual intent connectivity. This addresses sparsity issues and allows the model to make intent-grounded recommendations with an interpretable embedding translation layer. Through extensive experiments on real-world datasets, we demonstrate that IKGR overcomes knowledge gaps and achieves substantial gains over state-of-the-art baselines on both publicly available and our internal recommendation datasets.
