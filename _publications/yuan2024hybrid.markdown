---
layout: publication
title: 'A Hybrid RAG System With Comprehensive Enhancement On Complex Reasoning'
authors: Ye Yuan, Chengwu Liu, Jingyang Yuan, Gongbo Sun, Siqi Li, Ming Zhang
conference: "Arxiv"
year: 2024
bibkey: yuan2024hybrid
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.05141'}
  - {name: "Code", url: 'https://gitlab.aicrowd.com/shizueyy/crag-new'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'KDD', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) is a framework enabling large language
models (LLMs) to enhance their accuracy and reduce hallucinations by
integrating external knowledge bases. In this paper, we introduce a hybrid RAG
system enhanced through a comprehensive suite of optimizations that
significantly improve retrieval quality, augment reasoning capabilities, and
refine numerical computation ability. We refined the text chunks and tables in
web pages, added attribute predictors to reduce hallucinations, conducted LLM
Knowledge Extractor and Knowledge Graph Extractor, and finally built a
reasoning strategy with all the references. We evaluated our system on the CRAG
dataset through the Meta CRAG KDD Cup 2024 Competition. Both the local and
online evaluations demonstrate that our system significantly enhances complex
reasoning capabilities. In local evaluations, we have significantly improved
accuracy and reduced error rates compared to the baseline model, achieving a
notable increase in scores. In the meanwhile, we have attained outstanding
results in online assessments, demonstrating the performance and generalization
capabilities of the proposed system. The source code for our system is released
in \url\{https://gitlab.aicrowd.com/shizueyy/crag-new\}.
