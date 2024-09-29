---
layout: publication
title: 'News Without Borders: Domain Adaptation Of Multilingual Sentence Embeddings For Cross-lingual News Recommendation'
authors: Iana Andreea, Schmidt Fabian David, Glavaš Goran, Paulheim Heiko
conference: "Arxiv"
year: 2024
bibkey: iana2024news
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12634"}
tags: ['Few Shot', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Rapidly growing numbers of multilingual news consumers pose an increasing challenge to news recommender systems in terms of providing customized recommendations. First existing neural news recommenders even when powered by multilingual language models (LMs) suffer substantial performance losses in zero-shot cross-lingual transfer (ZS-XLT). Second the current paradigm of fine-tuning the backbone LM of a neural recommender on task-specific data is computationally expensive and infeasible in few-shot recommendation and cold-start setups where data is scarce or completely unavailable. In this work we propose a news-adapted sentence encoder (NaSE) domain-specialized from a pretrained massively multilingual sentence encoder (SE). To this end we construct and leverage PolyNews and PolyNewsParallel two multilingual news-specific corpora. With the news-adapted multilingual SE in place we test the effectiveness of (i.e. question the need for) supervised fine-tuning for news recommendation and propose a simple and strong baseline based on (i) frozen NaSE embeddings and (ii) late click-behavior fusion. We show that NaSE achieves state-of-the-art performance in ZS-XLT in true cold-start and few-shot news recommendation.
