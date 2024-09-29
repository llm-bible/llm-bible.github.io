---
layout: publication
title: Knowledge Adaptation from Large Language Model to Recommendation for Practical Industrial Application
authors: Jia Jian, Wang Yipei, Li Yan, Chen Honggang, Bai Xuehan, Liu Zhaocheng, Liang Jian, Chen Quan, Li Han, Jiang Peng, Gai Kun
conference: "Arxiv"
year: 2024
bibkey: jia2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03988"}
tags: ['Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Contemporary recommender systems predominantly rely on collaborative filtering techniques employing ID-embedding to capture latent associations among users and items. However this approach overlooks the wealth of semantic information embedded within textual descriptions of items leading to suboptimal performance in cold-start scenarios and long-tail user recommendations. Leveraging the capabilities of Large Language Models (LLMs) pretrained on massive text corpus presents a promising avenue for enhancing recommender systems by integrating open-world domain knowledge. In this paper we propose an Llm-driven knowlEdge Adaptive RecommeNdation (LEARN) framework that synergizes open-world knowledge with collaborative knowledge. We address computational complexity concerns by utilizing pretrained LLMs as item encoders and freezing LLM parameters to avoid catastrophic forgetting and preserve open-world knowledge. To bridge the gap between the open-world and collaborative domains we design a twin-tower structure supervised by the recommendation task and tailored for practical industrial application. Through offline experiments on the large-scale industrial dataset and online experiments on A/B tests we demonstrate the efficacy of our approach.
