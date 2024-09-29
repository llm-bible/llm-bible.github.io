---
layout: publication
title: News Without Borders Domain Adaptation Of Multilingual Sentence Embeddings For Cross45;lingual News Recommendation
authors: Iana Andreea, Schmidt Fabian David, Glavaš Goran, Paulheim Heiko
conference: "Arxiv"
year: 2024
bibkey: iana2024news
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12634"}
tags: ['Fine Tuning', 'Merging', 'RAG', 'Tools']
---
Rapidly growing numbers of multilingual news consumers pose an increasing challenge to news recommender systems in terms of providing customized recommendations. First existing neural news recommenders even when powered by multilingual language models (LMs) suffer substantial performance losses in zero45;shot cross45;lingual transfer (ZS45;XLT). Second the current paradigm of fine45;tuning the backbone LM of a neural recommender on task45;specific data is computationally expensive and infeasible in few45;shot recommendation and cold45;start setups where data is scarce or completely unavailable. In this work we propose a news45;adapted sentence encoder (NaSE) domain45;specialized from a pretrained massively multilingual sentence encoder (SE). To this end we construct and leverage PolyNews and PolyNewsParallel two multilingual news45;specific corpora. With the news45;adapted multilingual SE in place we test the effectiveness of (i.e. question the need for) supervised fine45;tuning for news recommendation and propose a simple and strong baseline based on (i) frozen NaSE embeddings and (ii) late click45;behavior fusion. We show that NaSE achieves state45;of45;the45;art performance in ZS45;XLT in true cold45;start and few45;shot news recommendation.
