---
layout: publication
title: Gecko Versatile Text Embeddings Distilled From Large Language Models
authors: Lee Jinhyuk, Dai Zhuyun, Ren Xiaoqi, Chen Blair, Cer Daniel, Cole Jeremy R., Hui Kai, Boratko Michael, Kapadia Rajvi, Ding Wen, Luan Yi, Duddu Sai Meher Karthik, Abrego Gustavo Hernandez, Shi Weiqiang, Gupta Nithi, Kusupati Aditya, Jain Prateek, Jonnalagadda Siddhartha Reddy, Chang Ming-wei, Naim Iftekhar
conference: "Arxiv"
year: 2024
bibkey: lee2024versatile
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20327"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG']
---
We present Gecko a compact and versatile text embedding model. Gecko achieves strong retrieval performance by leveraging a key idea distilling knowledge from large language models (LLMs) into a retriever. Our two45;step distillation process begins with generating diverse synthetic paired data using an LLM. Next we further refine the data quality by retrieving a set of candidate passages for each query and relabeling the positive and hard negative passages using the same LLM. The effectiveness of our approach is demonstrated by the compactness of the Gecko. On the Massive Text Embedding Benchmark (MTEB) Gecko with 256 embedding dimensions outperforms all existing entries with 768 embedding size. Gecko with 768 embedding dimensions achieves an average score of 66.31 competing with 7x larger models and 5x higher dimensional embeddings.
