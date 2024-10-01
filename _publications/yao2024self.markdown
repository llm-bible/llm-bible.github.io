---
layout: publication
title: 'Seakr: Self-aware Knowledge Retrieval For Adaptive Retrieval Augmented Generation'
authors: Yao Zijun, Qi Weijian, Pan Liangming, Cao Shulin, Hu Linmei, Liu Weichuan, Hou Lei, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: yao2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19215"}
  - {name: "Code", url: "https://github.com/THU-KEG/SeaKR"}
tags: ['Applications', 'Has Code', 'RAG']
---
This paper introduces Self-aware Knowledge Retrieval (SeaKR), a novel adaptive RAG model that extracts self-aware uncertainty of LLMs from their internal states. SeaKR activates retrieval when the LLMs present high self-aware uncertainty for generation. To effectively integrate retrieved knowledge snippets, SeaKR re-ranks them based on LLM's self-aware uncertainty to preserve the snippet that reduces their uncertainty to the utmost. To facilitate solving complex tasks that require multiple retrievals, SeaKR utilizes their self-aware uncertainty to choose among different reasoning strategies. Our experiments on both complex and simple Question Answering datasets show that SeaKR outperforms existing adaptive RAG methods. We release our code at https://github.com/THU-KEG/SeaKR.
