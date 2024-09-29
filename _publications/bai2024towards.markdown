---
layout: publication
title: 'Sparsellm: Towards Global Pruning For Pre-trained Language Models'
authors: Bai Guangji, Li Yijiang, Ling Chen, Kim Kibaek, Zhao Liang
conference: "Arxiv"
year: 2024
bibkey: bai2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17946"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pruning', 'RAG', 'Reinforcement Learning', 'Tools']
---
The transformative impact of large language models (LLMs) like LLaMA and GPT on natural language processing is countered by their prohibitive computational demands. Pruning has emerged as a pivotal compression strategy introducing sparsity to enhance both memory and computational efficiency. Yet traditional global pruning is impractical for LLMs due to scalability issues while local pruning despite its efficiency leads to suboptimal solutions. Addressing these challenges we propose SparseLLM a novel framework that redefines the global pruning process into manageable coordinated subproblems allowing for resource-efficient optimization with global optimality. SparseLLMs approach which conceptualizes LLMs as a chain of modular functions and leverages auxiliary variables for problem decomposition not only facilitates a pragmatic application on LLMs but also demonstrates significant performance improvements particularly in high-sparsity regimes where it surpasses current state-of-the-art methods.
