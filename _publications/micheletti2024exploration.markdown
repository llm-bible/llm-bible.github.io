---
layout: publication
title: 'Exploration Of Masked And Causal Language Modelling For Text Generation'
authors: Micheletti Nicolo, Belkadi Samuel, Han Lifeng, Nenadic Goran
conference: "Arxiv"
year: 2024
bibkey: micheletti2024exploration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12630"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Pretraining Methods']
---
Large Language Models (LLMs) have revolutionised the field of Natural Language Processing (NLP) and have achieved state-of-the-art performance in practically every task in this field. However the prevalent approach used in text generation Causal Language Modelling (CLM) which generates text sequentially from left to right inherently limits the freedom of the model which does not decide when and where each token is generated. In contrast Masked Language Modelling (MLM) primarily used for language understanding tasks can generate tokens anywhere in the text and any order. This paper conducts an extensive comparison of MLM and CLM approaches for text generation tasks. To do so we pre-train several language models of comparable sizes on three different datasets namely 1) medical discharge summaries 2) movie plot synopses and 3) authorship verification datasets. To assess the quality of the generations we first employ quantitative metrics and then perform a qualitative human evaluation to analyse coherence and grammatical correctness. In addition we evaluate the usefulness of the generated texts by using them in three different downstream tasks 1) Entity Recognition 2) Text Classification and 3) Authorship Verification. The results show that MLM consistently outperforms CLM in text generation across all datasets with higher quantitative scores and better coherence in the generated text. The study also finds (textit)no strong correlation between the quality of the generated text and the performance of the models in the downstream tasks. With this study we show that MLM for text generation has great potential for future research and provides direction for future studies in this area.
