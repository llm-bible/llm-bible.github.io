---
layout: publication
title: 'Understanding Privacy Risks Of Embeddings Induced By Large Language Models'
authors: Zhu Zhihao, Shao Ninglu, Lian Defu, Wu Chenwang, Liu Zheng, Yang Yi, Chen Enhong
conference: "Arxiv"
year: 2024
bibkey: zhu2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16587"}
tags: ['RAG', 'Reinforcement Learning']
---
Large language models (LLMs) show early signs of artificial general
intelligence but struggle with hallucinations. One promising solution to
mitigate these hallucinations is to store external knowledge as embeddings,
aiding LLMs in retrieval-augmented generation. However, such a solution risks
compromising privacy, as recent studies experimentally showed that the original
text can be partially reconstructed from text embeddings by pre-trained
language models. The significant advantage of LLMs over traditional pre-trained
models may exacerbate these concerns. To this end, we investigate the
effectiveness of reconstructing original knowledge and predicting entity
attributes from these embeddings when LLMs are employed. Empirical findings
indicate that LLMs significantly improve the accuracy of two evaluated tasks
over those from pre-trained models, regardless of whether the texts are
in-distribution or out-of-distribution. This underscores a heightened potential
for LLMs to jeopardize user privacy, highlighting the negative consequences of
their widespread use. We further discuss preliminary strategies to mitigate
this risk.
