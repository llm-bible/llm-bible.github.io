---
layout: publication
title: W-RAG Weakly Supervised Dense Retrieval in RAG for Open-domain Question Answering
authors: Nian Jinming, Peng Zhiyuan, Wang Qifan, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: nian2024w
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08444"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
In knowledge-intensive tasks such as open-domain question answering (OpenQA) Large Language Models (LLMs) often struggle to generate factual answers relying solely on their internal (parametric) knowledge. To address this limitation Retrieval-Augmented Generation (RAG) systems enhance LLMs by retrieving relevant information from external sources thereby positioning the retriever as a pivotal component. Although dense retrieval demonstrates state-of-the-art performance its training poses challenges due to the scarcity of ground-truth evidence largely attributed to the high costs of human annotation. In this paper we propose W-RAG by utilizing the ranking capabilities of LLMs to create weakly labeled data for training dense retrievers. Specifically we rerank the top-K passages retrieved via BM25 by assessing the probability that LLMs will generate the correct answer based on the question and each passage. The highest-ranking passages are then used as positive training examples for dense retrieval. Our comprehensive experiments across four publicly available OpenQA datasets demonstrate that our approach enhances both retrieval and OpenQA performance compared to baseline models.
