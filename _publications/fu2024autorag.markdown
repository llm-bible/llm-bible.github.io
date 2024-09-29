---
layout: publication
title: Autorag45;hp Automatic Online Hyper45;parameter Tuning For Retrieval45;augmented Generation
authors: Fu Jia, Qin Xiaoting, Yang Fangkai, Wang Lu, Zhang Jue, Lin Qingwei, Chen Yubo, Zhang Dongmei, Rajmohan Saravan, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: fu2024autorag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19251"}
  - {name: "Code", url: "https://aka.ms/autorag"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
Recent advancements in Large Language Models have transformed ML/AI development necessitating a reevaluation of AutoML principles for the Retrieval45;Augmented Generation (RAG) systems. To address the challenges of hyper45;parameter optimization and online adaptation in RAG we propose the AutoRAG45;HP framework which formulates the hyper45;parameter tuning as an online multi45;armed bandit (MAB) problem and introduces a novel two45;level Hierarchical MAB (Hier45;MAB) method for efficient exploration of large search spaces. We conduct extensive experiments on tuning hyper45;parameters such as top45;k retrieved documents prompt compression ratio and embedding methods using the ALCE45;ASQA and Natural Questions datasets. Our evaluation from jointly optimization all three hyper45;parameters demonstrate that MAB45;based online learning methods can achieve Recall35;64;5 ≈ 0.8 for scenarios with prominent gradients in search space using only sim2037; of the LLM API calls required by the Grid Search approach. Additionally the proposed Hier45;MAB approach outperforms other baselines in more challenging optimization scenarios. The code will be made available at https://aka.ms/autorag.
