---
layout: publication
title: 'RAG-VR: Leveraging Retrieval-augmented Generation For 3D Question Answering In VR Environments'
authors: Shiyi Ding, Ying Chen
conference: "Arxiv"
year: 2025
bibkey: ding2025rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08256'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
Recent advances in large language models (LLMs) provide new opportunities for
context understanding in virtual reality (VR). However, VR contexts are often
highly localized and personalized, limiting the effectiveness of
general-purpose LLMs. To address this challenge, we present RAG-VR, the first
3D question-answering system for VR that incorporates retrieval-augmented
generation (RAG), which augments an LLM with external knowledge retrieved from
a localized knowledge database to improve the answer quality. RAG-VR includes a
pipeline for extracting comprehensive knowledge about virtual environments and
user conditions for accurate answer generation. To ensure efficient retrieval,
RAG-VR offloads the retrieval process to a nearby edge server and uses only
essential information during retrieval. Moreover, we train the retriever to
effectively distinguish among relevant, irrelevant, and hard-to-differentiate
information in relation to questions. RAG-VR improves answer accuracy by
17.9%-41.8% and reduces end-to-end latency by 34.5%-47.3% compared with two
baseline systems.
