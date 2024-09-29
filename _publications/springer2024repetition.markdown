---
layout: publication
title: Repetition Improves Language Model Embeddings
authors: Springer Jacob Mitchell, Kotha Suhas, Fried Daniel, Neubig Graham, Raghunathan Aditi
conference: "Arxiv"
year: 2024
bibkey: springer2024repetition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15449"}
tags: ['GPT', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Recent approaches to improving the extraction of text embeddings from autoregressive large language models (LLMs) have largely focused on improvements to data backbone pretrained language models or improving task45;differentiation via instructions. In this work we address an architectural limitation of autoregressive models token embeddings cannot contain information from tokens that appear later in the input. To address this limitation we propose a simple approach echo embeddings in which we repeat the input twice in context and extract embeddings from the second occurrence. We show that echo embeddings of early tokens can encode information about later tokens allowing us to maximally leverage high45;quality LLMs for embeddings. On the MTEB leaderboard echo embeddings improve over classical embeddings by over 937; zero45;shot and by around 0.737; when fine45;tuned. Echo embeddings with a Mistral45;7B model achieve state45;of45;the45;art compared to prior open source models that do not leverage synthetic fine45;tuning data.
