---
layout: publication
title: 'Cross-lingual Pitfalls: Automatic Probing Cross-lingual Weakness Of Multilingual Large Language Models'
authors: Zixiang Xu, Yanbo Wang, Yue Huang, Xiuying Chen, Jieyu Zhao, Meng Jiang, Xiangliang Zhang
conference: "Arxiv"
year: 2025
bibkey: xu2025cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18673"}
  - {name: "Code", url: "https://github.com/xzx34/Cross-Lingual-Pitfalls"}
tags: ['RAG', 'Training Techniques', 'Has Code']
---
Large Language Models (LLMs) have achieved remarkable success in Natural Language Processing (NLP), yet their cross-lingual performance consistency remains a significant challenge. This paper introduces a novel methodology for efficiently identifying inherent cross-lingual weaknesses in LLMs. Our approach leverages beam search and LLM-based simulation to generate bilingual question pairs that expose performance discrepancies between English and target languages. We construct a new dataset of over 6,000 bilingual pairs across 16 languages using this methodology, demonstrating its effectiveness in revealing weaknesses even in state-of-the-art models. The extensive experiments demonstrate that our method precisely and cost-effectively pinpoints cross-lingual weaknesses, consistently revealing over 50% accuracy drops in target languages across a wide range of models. Moreover, further experiments investigate the relationship between linguistic similarity and cross-lingual weaknesses, revealing that linguistically related languages share similar performance patterns and benefit from targeted post-training. Code is available at https://github.com/xzx34/Cross-Lingual-Pitfalls.
