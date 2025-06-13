---
layout: publication
title: 'Improving Factual Consistency Of News Summarization By Contrastive Preference Optimization'
authors: Huawen Feng, Yan Fan, Xiong Liu, Ting-en Lin, Zekun Yao, Yuchuan Wu, Fei Huang, Yongbin Li, Qianli Ma
conference: "Arxiv"
year: 2023
bibkey: feng2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19347"}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'Efficiency and Optimization']
---
Despite the recent progress in news summarization made by large language
models (LLMs), they often generate summaries that are factually inconsistent
with original articles, known as "hallucinations" in text generation. Unlike
previous small models (e.g., BART, T5), current LLMs make fewer silly mistakes
but more sophisticated ones, such as imposing cause and effect, adding false
details, overgeneralizing, etc. These hallucinations are challenging to detect
through traditional methods, which poses great challenges for improving the
factual consistency of text summarization. In this paper, we propose
Contrastive Preference Optimization (CPO) to disentangle the LLMs' propensities
to generate faithful and fake content. Furthermore, we adopt a probing-based
specific training method to improve their capacity of distinguishing two types
of propensities. In this way, LLMs can execute the instructions more accurately
and have enhanced perception of hallucinations. Experimental results show that
CPO significantly improves the reliability of summarization based on LLMs.
