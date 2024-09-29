---
layout: publication
title: Retrieval45;augmented Generation For Knowledge45;intensive NLP Tasks
authors: Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela
conference: "Arxiv"
year: 2020
bibkey: lewis2020retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2005.11401v4"}
tags: ['Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large pre45;trained language models have been shown to store factual knowledge in their parameters and achieve state45;of45;the45;art results when fine45;tuned on downstream NLP tasks. However their ability to access and precisely manipulate knowledge is still limited and hence on knowledge45;intensive tasks their performance lags behind task45;specific architectures. Additionally providing provenance for their decisions and updating their world knowledge remain open research problems. Pre45;trained models with a differentiable access mechanism to explicit non45;parametric memory can overcome this issue but have so far been only investigated for extractive downstream tasks. We explore a general45;purpose fine45;tuning recipe for retrieval45;augmented generation (RAG) 45;45; models which combine pre45;trained parametric and non45;parametric memory for language generation. We introduce RAG models where the parametric memory is a pre45;trained seq2seq model and the non45;parametric memory is a dense vector index of Wikipedia accessed with a pre45;trained neural retriever. We compare two RAG formulations one which conditions on the same retrieved passages across the whole generated sequence the other can use different passages per token. We fine45;tune and evaluate our models on a wide range of knowledge45;intensive NLP tasks and set the state45;of45;the45;art on three open domain QA tasks outperforming parametric seq2seq models and task45;specific retrieve45;and45;extract architectures. For language generation tasks we find that RAG models generate more specific diverse and factual language than a state45;of45;the45;art parametric45;only seq2seq baseline.
