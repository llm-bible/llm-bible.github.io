---
layout: publication
title: Stacking Your Transformers A Closer Look at Model Growth for Efficient LLM Pre-Training
authors: Du Wenyu, Luo Tongxu, Qiu Zihan, Huang Zeyu, Shen Yikang, Cheng Reynold, Guo Yike, Fu Jie
conference: "Arxiv"
year: 2024
bibkey: du2024stacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15319"}
  - {name: "Code", url: "https://llm-stacking.github.io/"}
  - {name: "Code", url: "https://llm-stacking.github.io/"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'TACL', 'Training Techniques', 'Transformer']
---
LLMs are computationally expensive to pre-train due to their large scale. Model growth emerges as a promising approach by leveraging smaller models to accelerate the training of larger ones. However the viability of these model growth methods in efficient LLM pre-training remains underexplored. This work identifies three critical underlinetextitObstacles (textitO1) lack of comprehensive evaluation (textitO2) untested viability for scaling and (textitO3) lack of empirical guidelines. To tackle textitO1 we summarize existing approaches into four atomic growth operators and systematically evaluate them in a standardized LLM pre-training setting. Our findings reveal that a depthwise stacking operator called G_textstack exhibits remarkable acceleration in training leading to decreased loss and improved overall performance on eight standard NLP benchmarks compared to strong baselines. Motivated by these promising results we conduct extensive experiments to delve deeper into G_textstack to address textitO2 and textitO3. For textitO2 (untested scalability) our study shows that G_textstack is scalable and consistently performs well with experiments up to 7B LLMs after growth and pre-training LLMs with 750B tokens. For example compared to a conventionally trained 7B model using 300B tokens our G_textstack model converges to the same loss with 194B tokens resulting in a 54.6 speedup. We further address textitO3 (lack of empirical guidelines) by formalizing guidelines to determine growth timing and growth factor for G_textstack making it practical in general LLM pre-training. We also provide in-depth discussions and comprehensive ablation studies of G_textstack. Our code and pre-trained model are available at href https://llm-stacking.github.io/ https://llm-stacking.github.io/.
