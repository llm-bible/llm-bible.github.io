---
layout: publication
title: 'Analyzing Llms'' Knowledge Boundary Cognition Across Languages Through The Lens Of Internal Representations'
authors: Chenghao Xiao, Hou Pong Chan, Hao Zhang, Mahani Aljunied, Lidong Bing, Noura Al Moubayed, Yu Rong
conference: "Arxiv"
year: 2025
bibkey: xiao2025analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13816"}
  - {name: "Code", url: "https://github.com/DAMO-NLP-SG/LLM-Multilingual-Knowledge-Boundaries"}
tags: ['Fine-Tuning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
While understanding the knowledge boundaries of LLMs is crucial to prevent
hallucination, research on knowledge boundaries of LLMs has predominantly
focused on English. In this work, we present the first study to analyze how
LLMs recognize knowledge boundaries across different languages by probing their
internal representations when processing known and unknown questions in
multiple languages. Our empirical studies reveal three key findings: 1) LLMs'
perceptions of knowledge boundaries are encoded in the middle to middle-upper
layers across different languages. 2) Language differences in knowledge
boundary perception follow a linear structure, which motivates our proposal of
a training-free alignment method that effectively transfers knowledge boundary
perception ability across languages, thereby helping reduce hallucination risk
in low-resource languages; 3) Fine-tuning on bilingual question pair
translation further enhances LLMs' recognition of knowledge boundaries across
languages. Given the absence of standard testbeds for cross-lingual knowledge
boundary analysis, we construct a multilingual evaluation suite comprising
three representative types of knowledge boundary data. Our code and datasets
are publicly available at
https://github.com/DAMO-NLP-SG/LLM-Multilingual-Knowledge-Boundaries.
