---
layout: publication
title: 'Avoid Recommending Out-of-domain Items: Constrained Generative Recommendation With Llms'
authors: Hao Liao, Wensheng Lu, Jianxun Lian, Mingqi Wu, Shuo Wang, Yong Zhang, Yitian Huang, Mingyang Zhou, Xing Xie
conference: "Arxiv"
year: 2025
bibkey: liao2025avoid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03336"}
  - {name: "Code", url: "https://github.com/microsoft/RecAI"}
tags: ['Has Code', 'Uncategorized']
---
Large Language Models (LLMs) have shown promise for generative recommender
systems due to their transformative capabilities in user interaction. However,
ensuring they do not recommend out-of-domain (OOD) items remains a challenge.
We study two distinct methods to address this issue: RecLM-ret, a
retrieval-based method, and RecLM-cgen, a constrained generation method. Both
methods integrate seamlessly with existing LLMs to ensure in-domain
recommendations. Comprehensive experiments on three recommendation datasets
demonstrate that RecLM-cgen consistently outperforms RecLM-ret and existing
LLM-based recommender models in accuracy while eliminating OOD recommendations,
making it the preferred method for adoption. Additionally, RecLM-cgen maintains
strong generalist capabilities and is a lightweight plug-and-play module for
easy integration into LLMs, offering valuable practical benefits for the
community. Source code is available at https://github.com/microsoft/RecAI
