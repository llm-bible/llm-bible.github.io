---
layout: publication
title: W45;RAG Weakly Supervised Dense Retrieval In RAG For Open45;domain Question Answering
authors: Nian Jinming, Peng Zhiyuan, Wang Qifan, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: nian2024w
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08444"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
In knowledge45;intensive tasks such as open45;domain question answering (OpenQA) Large Language Models (LLMs) often struggle to generate factual answers relying solely on their internal (parametric) knowledge. To address this limitation Retrieval45;Augmented Generation (RAG) systems enhance LLMs by retrieving relevant information from external sources thereby positioning the retriever as a pivotal component. Although dense retrieval demonstrates state45;of45;the45;art performance its training poses challenges due to the scarcity of ground45;truth evidence largely attributed to the high costs of human annotation. In this paper we propose W45;RAG by utilizing the ranking capabilities of LLMs to create weakly labeled data for training dense retrievers. Specifically we rerank the top45;K passages retrieved via BM25 by assessing the probability that LLMs will generate the correct answer based on the question and each passage. The highest45;ranking passages are then used as positive training examples for dense retrieval. Our comprehensive experiments across four publicly available OpenQA datasets demonstrate that our approach enhances both retrieval and OpenQA performance compared to baseline models.
