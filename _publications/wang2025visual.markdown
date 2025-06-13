---
layout: publication
title: 'Vidorag: Visual Document Retrieval-augmented Generation Via Dynamic Iterative Reasoning Agents'
authors: Qiuchen Wang, Ruixue Ding, Zehui Chen, Weiqi Wu, Shihang Wang, Pengjun Xie, Feng Zhao
conference: "Arxiv"
year: 2025
bibkey: wang2025visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18017'}
  - {name: "Code", url: 'https://github.com/Alibaba-NLP/ViDoRAG'}
tags: ['Agentic', 'Has Code', 'RAG', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
Understanding information from visually rich documents remains a significant challenge for traditional Retrieval-Augmented Generation (RAG) methods. Existing benchmarks predominantly focus on image-based question answering (QA), overlooking the fundamental challenges of efficient retrieval, comprehension, and reasoning within dense visual documents. To bridge this gap, we introduce ViDoSeek, a novel dataset designed to evaluate RAG performance on visually rich documents requiring complex reasoning. Based on it, we identify key limitations in current RAG approaches: (i) purely visual retrieval methods struggle to effectively integrate both textual and visual features, and (ii) previous approaches often allocate insufficient reasoning tokens, limiting their effectiveness. To address these challenges, we propose ViDoRAG, a novel multi-agent RAG framework tailored for complex reasoning across visual documents. ViDoRAG employs a Gaussian Mixture Model (GMM)-based hybrid strategy to effectively handle multi-modal retrieval. To further elicit the model's reasoning capabilities, we introduce an iterative agent workflow incorporating exploration, summarization, and reflection, providing a framework for investigating test-time scaling in RAG domains. Extensive experiments on ViDoSeek validate the effectiveness and generalization of our approach. Notably, ViDoRAG outperforms existing methods by over 10% on the competitive ViDoSeek benchmark. The code is available at https://github.com/Alibaba-NLP/ViDoRAG.
