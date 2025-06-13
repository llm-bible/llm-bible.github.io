---
layout: publication
title: 'MEXA: Multilingual Evaluation Of English-centric Llms Via Cross-lingual Alignment'
authors: Amir Hossein Kargaran, Ali Modarressi, Nafiseh Nikeghbal, Jana Diesner, François Yvon, Hinrich Schütze
conference: "Arxiv"
year: 2024
bibkey: kargaran2024multilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05873'}
  - {name: "Code", url: 'https://cis-lmu-mexa.hf.space,'}
  - {name: "Code", url: 'https://github.com/cisnlp/MEXA'}
tags: ['RAG', 'Has Code']
---
English-centric large language models (LLMs) often show strong multilingual capabilities. However, their multilingual performance remains unclear and is under-evaluated for many other languages. Most benchmarks for multilinguality focus on classic NLP tasks or cover a minimal number of languages. We introduce MEXA, a method for assessing the multilingual capabilities of pre-trained English-centric LLMs using parallel sentences, which are available for more languages than existing downstream tasks. MEXA leverages that English-centric LLMs use English as a pivot language in their intermediate layers. MEXA computes the alignment between English and non-English languages using parallel sentences to evaluate the transfer of language understanding from English to other languages. This alignment can be used to estimate model performance in different languages. We conduct controlled experiments using various parallel datasets (FLORES-200 and Bible), models (Llama family, Gemma family, Mistral, and OLMo), and established downstream tasks (Belebele, m-MMLU, and m-ARC). We explore different methods to compute embeddings in decoder-only models. Our results show that MEXA, in its default settings, achieves an average Pearson correlation of 0.90 between its predicted scores and actual task performance across languages. This suggests that MEXA is a reliable method for estimating the multilingual capabilities of English-centric LLMs, providing a clearer understanding of their multilingual potential and the inner workings of LLMs. Leaderboard: https://cis-lmu-mexa.hf.space, Code: https://github.com/cisnlp/MEXA.
