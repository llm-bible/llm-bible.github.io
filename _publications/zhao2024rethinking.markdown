---
layout: publication
title: 'Lens: Rethinking Multilingual Enhancement For Large Language Models'
authors: Weixiang Zhao, Yulin Hu, Jiahe Guo, Xingyu Sui, Tongtong Wu, Yang Deng, Yanyan Zhao, Bing Qin, Wanxiang Che, Ting Liu
conference: "Arxiv"
year: 2024
bibkey: zhao2024rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04407'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Pre-Training']
---
As global demand for multilingual large language models (LLMs) grows, most LLMs still remain overly focused on English, leading to the limited access to advanced AI for non-English speakers. Current methods to enhance multilingual capabilities largely rely on data-driven post-training techniques, such as multilingual instruction tuning or continual pre-training. However, these approaches exhibit significant limitations, including high resource cost, exacerbation of off-target issue and catastrophic forgetting of central language abilities. To this end, we propose Lens, a novel approach that enhances multilingual capabilities by leveraging LLMs' internal language representation spaces. Lens operates on two subspaces: the language-agnostic subspace, where it aligns target languages with the central language to inherit strong semantic representations, and the language-specific subspace, where it separates target and central languages to preserve linguistic specificity. Experiments on three English-centric LLMs show that Lens significantly improves multilingual performance while maintaining the model's English proficiency, achieving better results with less computational cost compared to existing post-training approaches.
