---
layout: publication
title: 'Banglabyt5: Byte-level Modelling For Bangla'
authors: Pramit Bhattacharyya, Arnab Bhattacharya
conference: "Arxiv"
year: 2025
bibkey: bhattacharyya2025byte
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17102"}
tags: ['Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved remarkable success across various natural language processing tasks. However, most LLM models use traditional tokenizers like BPE and SentencePiece, which fail to capture the finer nuances of a morphologically rich language like Bangla (Bengali). In this work, we introduce BanglaByT5, the first byte-level encoder-decoder model explicitly tailored for Bangla. Built upon a small variant of Googles ByT5 architecture, BanglaByT5 is pre-trained on a 14GB curated corpus combining high-quality literary and newspaper articles. Through zeroshot and supervised evaluations across generative and classification tasks, BanglaByT5 demonstrates competitive performance, surpassing several multilingual and larger models. Our findings highlight the efficacy of byte-level modelling for morphologically rich languages and highlight BanglaByT5 potential as a lightweight yet powerful tool for Bangla NLP, particularly in both resource-constrained and scalable environments.
