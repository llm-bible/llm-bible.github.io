---
layout: publication
title: Open45;source Large Language Models Are Strong Zero45;shot Query Likelihood Models For Document Ranking
authors: Zhuang Shengyao, Liu Bing, Koopman Bevan, Zuccon Guido
conference: "Arxiv"
year: 2023
bibkey: zhuang2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13243"}
  - {name: "Code", url: "https://github.com/ielab/llm&#45;qlm"}
tags: ['Applications', 'Has Code']
---
In the field of information retrieval Query Likelihood Models (QLMs) rank documents based on the probability of generating the query given the content of a document. Recently advanced large language models (LLMs) have emerged as effective QLMs showcasing promising ranking capabilities. This paper focuses on investigating the genuine zero45;shot ranking effectiveness of recent LLMs which are solely pre45;trained on unstructured text data without supervised instruction fine45;tuning. Our findings reveal the robust zero45;shot ranking ability of such LLMs highlighting that additional instruction fine45;tuning may hinder effectiveness unless a question generation task is present in the fine45;tuning dataset. Furthermore we introduce a novel state45;of45;the45;art ranking system that integrates LLM45;based QLMs with a hybrid zero45;shot retriever demonstrating exceptional effectiveness in both zero45;shot and few45;shot scenarios. We make our codebase publicly available at https://github.com/ielab/llm&#45;qlm.
