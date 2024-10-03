---
layout: publication
title: 'Echosight: Advancing Visual-language Models With Wiki Knowledge'
authors: Yan Yibin, Xie Weidi
conference: "Arxiv"
year: 2024
bibkey: yan2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12735"}
tags: ['Applications', 'Multimodal Models', 'RAG', 'Tools']
---
Knowledge-based Visual Question Answering (KVQA) tasks require answering questions about images using extensive background knowledge. Despite significant advancements, generative models often struggle with these tasks due to the limited integration of external knowledge. In this paper, we introduce EchoSight, a novel multimodal Retrieval-Augmented Generation (RAG) framework that enables large language models (LLMs) to answer visual questions requiring fine-grained encyclopedic knowledge. To strive for high-performing retrieval, EchoSight first searches wiki articles by using visual-only information, subsequently, these candidate articles are further reranked according to their relevance to the combined text-image query. This approach significantly improves the integration of multimodal knowledge, leading to enhanced retrieval outcomes and more accurate VQA responses. Our experimental results on the Encyclopedic VQA and InfoSeek datasets demonstrate that EchoSight establishes new state-of-the-art results in knowledge-based VQA, achieving an accuracy of 41.8&#37; on Encyclopedic VQA and 31.3&#37; on InfoSeek.
