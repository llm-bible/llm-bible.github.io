---
layout: publication
title: Autorag-hp Automatic Online Hyper-parameter Tuning For Retrieval-augmented Generation
authors: Fu Jia, Qin Xiaoting, Yang Fangkai, Wang Lu, Zhang Jue, Lin Qingwei, Chen Yubo, Zhang Dongmei, Rajmohan Saravan, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: fu2024autorag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19251"}
  - {name: "Code", url: "https://aka.ms/autorag"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Prompting', 'RAG', 'Tools']
---
Recent advancements in Large Language Models have transformed ML/AI development necessitating a reevaluation of AutoML principles for the Retrieval-Augmented Generation (RAG) systems. To address the challenges of hyper-parameter optimization and online adaptation in RAG we propose the AutoRAG-HP framework which formulates the hyper-parameter tuning as an online multi-armed bandit (MAB) problem and introduces a novel two-level Hierarchical MAB (Hier-MAB) method for efficient exploration of large search spaces. We conduct extensive experiments on tuning hyper-parameters such as top-k retrieved documents prompt compression ratio and embedding methods using the ALCE-ASQA and Natural Questions datasets. Our evaluation from jointly optimization all three hyper-parameters demonstrate that MAB-based online learning methods can achieve Recall35;64;5 (approx) 0.8 for scenarios with prominent gradients in search space using only (sim)2037; of the LLM API calls required by the Grid Search approach. Additionally the proposed Hier-MAB approach outperforms other baselines in more challenging optimization scenarios. The code will be made available at https://aka.ms/autorag.
