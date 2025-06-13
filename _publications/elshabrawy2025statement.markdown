---
layout: publication
title: 'Statement-tuning Enables Efficient Cross-lingual Generalization In Encoder-only Models'
authors: Ahmed Elshabrawy, Thanh-nhi Nguyen, Yeeun Kang, Lihan Feng, Annant Jain, Faadil Abdullah Shaikh, Jonibek Mansurov, Mohamed Fazli Mohamed Imam, Jesus-german Ortiz-barajas, Rendi Chevi, Alham Fikri Aji
conference: "Arxiv"
year: 2025
bibkey: elshabrawy2025statement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01592"}
tags: ['BERT', 'Few-Shot', 'Efficiency and Optimization', 'Model Architecture']
---
Large Language Models (LLMs) excel in zero-shot and few-shot tasks, but achieving similar performance with encoder-only models like BERT and RoBERTa has been challenging due to their architecture. However, encoders offer advantages such as lower computational and memory costs. Recent work adapts them for zero-shot generalization using Statement Tuning, which reformulates tasks into finite templates. We extend this approach to multilingual NLP, exploring whether encoders can achieve zero-shot cross-lingual generalization and serve as efficient alternatives to memory-intensive LLMs for low-resource languages. Our results show that state-of-the-art encoder models generalize well across languages, rivaling multilingual LLMs while being more efficient. We also analyze multilingual Statement Tuning dataset design, efficiency gains, and language-specific generalization, contributing to more inclusive and resource-efficient NLP models. We release our code and models.
