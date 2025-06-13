---
layout: publication
title: 'Insights Into LLM Long-context Failures: When Transformers Know But Don''t Tell'
authors: Taiming Lu, Muhan Gao, Kuai Yu, Adam Byerly, Daniel Khashabi
conference: "Arxiv"
year: 2024
bibkey: lu2024insights
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14673"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Applications']
---
Large Language Models (LLMs) exhibit positional bias, struggling to utilize
information from the middle or end of long contexts. Our study explores LLMs'
long-context reasoning by probing their hidden representations. We find that
while LLMs encode the position of target information, they often fail to
leverage this in generating accurate responses. This reveals a disconnect
between information retrieval and utilization, a "know but don't tell"
phenomenon. We further analyze the relationship between extraction time and
final accuracy, offering insights into the underlying mechanics of transformer
models.
