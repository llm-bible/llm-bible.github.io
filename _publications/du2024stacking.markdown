---
layout: publication
title: Stacking Your Transformers A Closer Look at Model Growth for Efficient LLM Pre-Training
authors: Du Wenyu, Luo Tongxu, Qiu Zihan, Huang Zeyu, Shen Yikang, Cheng Reynold, Guo Yike, Fu Jie
conference: "Arxiv"
year: 2024
bibkey: du2024stacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15319"}
  - {name: "Code", url: "https://llm-stacking.github.io/}{https://llm-stacking.github.io/}$"}
tags: ['Transformer', 'Arxiv', 'Has Code', 'LLM', 'Model Architecture', 'A']
---
LLMs are computationally expensive to pre-train due to their large scale. Model growth emerges as a promising approach by leveraging smaller models to accelerate the training of larger ones. However the viability of these model growth methods in efficient LLM pre-training remains underexplored. This work identifies three critical bstacles (1) lack of comprehensive evaluation (2) untested viability for scaling and (3) lack of empirical guidelines. To tackle 1 we summarize existing approaches into four atomic growth operators and systematically evaluate them in a standardized LLM pre-training setting. Our findings reveal that a depthwise stacking operator called G_ exhibits remarkable acceleration in training leading to decreased loss and improved overall performance on eight standard NLP benchmarks compared to strong baselines. Motivated by these promising results we conduct extensive experiments to delve deeper into G_ to address 2 and 3. For 2 (untested scalability) our study shows that G_ is scalable and consistently performs well with experiments up to 7B LLMs after growth and pre-training LLMs with 750B tokens. For example compared to a conventionally trained 7B model using 300B tokens our G_ model converges to the same loss with 194B tokens resulting in a 54.6 speedup. We further address 3 (lack of empirical guidelines) by formalizing guidelines to determine growth timing and growth factor for G_ making it practical in general LLM pre-training. We also provide in-depth discussions and comprehensive ablation studies of G_. Our code and pre-trained model are available at hrefhttps://llm-stacking.github.io/}{https://llm-stacking.github.io/}$.
