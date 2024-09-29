---
layout: publication
title: Longrag Enhancing Retrieval-augmented Generation With Long-context Llms
authors: Jiang Ziyan, Ma Xueguang, Chen Wenhu
conference: "Arxiv"
year: 2024
bibkey: jiang2024longrag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15319"}
tags: ['RAG', 'Tools', 'Training Techniques']
---
In traditional RAG framework the basic retrieval units are normally short. The common retrievers like DPR normally work with 100-word Wikipedia paragraphs. Such a design forces the retriever to search over a large corpus to find the needle unit. In contrast the readers only need to generate answers from the short retrieved units. The imbalanced heavy retriever and light reader design can lead to sub-optimal performance. The loss of contextual information in the short chunked units may increase the likelihood of introducing hard negatives during the retrieval stage. Additionally the reader might not fully leverage the capabilities of recent advancements in LLMs. In order to alleviate the imbalance we propose a new framework LongRAG consisting of a long retriever and a long reader. In the two Wikipedia-based datasets NQ and HotpotQA LongRAG processes the entire Wikipedia corpus into 4K-token units by grouping related documents. By increasing the unit size we significantly reduce the total number of units. This greatly reduces the burden on the retriever resulting in strong retrieval performance with only a few (less than 8) top units. Without requiring any training LongRAG achieves an EM of 62.737; on NQ and 64.337; on HotpotQA which are on par with the (fully-trained) SoTA model. Furthermore we test on two non-Wikipedia-based datasets Qasper and MultiFieldQA-en. LongRAG processes each individual document as a single (long) unit rather than chunking them into smaller units. By doing so we achieve an F1 score of 25.937; on Qasper and 57.537; on MultiFieldQA-en. Our study offers insights into the future roadmap for combining RAG with long-context LLMs.
