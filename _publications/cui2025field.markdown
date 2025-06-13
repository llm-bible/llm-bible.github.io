---
layout: publication
title: 'Field Matters: A Lightweight Llm-enhanced Method For CTR Prediction'
authors: Yu Cui, Feng Liu, Jiawei Chen, Xingyu Lou, Changwang Zhang, Jun Wang, Yuegang Sun, Xiaohu Yang, Can Wang
conference: "Arxiv"
year: 2025
bibkey: cui2025field
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14057'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/LLaCTR-EC46'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'RecSys', 'Pretraining Methods']
---
Click-through rate (CTR) prediction is a fundamental task in modern recommender systems. In recent years, the integration of large language models (LLMs) has been shown to effectively enhance the performance of traditional CTR methods. However, existing LLM-enhanced methods often require extensive processing of detailed textual descriptions for large-scale instances or user/item entities, leading to substantial computational overhead. To address this challenge, this work introduces LLaCTR, a novel and lightweight LLM-enhanced CTR method that employs a field-level enhancement paradigm. Specifically, LLaCTR first utilizes LLMs to distill crucial and lightweight semantic knowledge from small-scale feature fields through self-supervised field-feature fine-tuning. Subsequently, it leverages this field-level semantic knowledge to enhance both feature representation and feature interactions. In our experiments, we integrate LLaCTR with six representative CTR models across four datasets, demonstrating its superior performance in terms of both effectiveness and efficiency compared to existing LLM-enhanced methods. Our code is available at https://anonymous.4open.science/r/LLaCTR-EC46.
