---
layout: publication
title: 'Pre-training With Large Language Model-based Document Expansion For Dense Passage Retrieval'
authors: Ma Guangyuan, Wu Xing, Wang Peng, Lin Zijia, Hu Songlin
conference: "Arxiv"
year: 2023
bibkey: ma2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08285"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
In this paper we systematically study the potential of pre-training with Large Language Model(LLM)-based document expansion for dense passage retrieval. Concretely we leverage the capabilities of LLMs for document expansion i.e. query generation and effectively transfer expanded knowledge to retrievers using pre-training strategies tailored for passage retrieval. These strategies include contrastive learning and bottlenecked query generation. Furthermore we incorporate a curriculum learning strategy to reduce the reliance on LLM inferences. Experimental results demonstrate that pre-training with LLM-based document expansion significantly boosts the retrieval performance on large-scale web-search tasks. Our work shows strong zero-shot and out-of-domain retrieval abilities making it more widely applicable for retrieval when initializing with no human-labeled data.
