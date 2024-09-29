---
layout: publication
title: Retrieve Summarize Plan Advancing Multi-hop Question Answering with an Iterative Approach
authors: Jiang Zhouyu, Sun Mengshu, Liang Lei, Zhang Zhiqiang
conference: "Arxiv"
year: 2024
bibkey: jiang2024retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13101"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Security']
---
Multi-hop question answering is a challenging task with distinct industrial relevance and Retrieval-Augmented Generation (RAG) methods based on large language models (LLMs) have become a popular approach to tackle this task. Owing to the potential inability to retrieve all necessary information in a single iteration a series of iterative RAG methods has been recently developed showing significant performance improvements. However existing methods still face two critical challenges context overload resulting from multiple rounds of retrieval and over-planning and repetitive planning due to the lack of a recorded retrieval trajectory. In this paper we propose a novel iterative RAG method called ReSP equipped with a dual-function summarizer. This summarizer compresses information from retrieved documents targeting both the overarching question and the current sub-question concurrently. Experimental results on the multi-hop question-answering datasets HotpotQA and 2WikiMultihopQA demonstrate that our method significantly outperforms the state-of-the-art and exhibits excellent robustness concerning context length.
