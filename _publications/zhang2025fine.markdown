---
layout: publication
title: 'Fine-grained Retrieval-augmented Generation For Visual Question Answering'
authors: Zhengxuan Zhang, Yin Wu, Yuyu Luo, Nan Tang
conference: "Arxiv"
year: 2025
bibkey: zhang2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20964"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Applications']
---
Visual Question Answering (VQA) focuses on providing answers to natural
language questions by utilizing information from images. Although cutting-edge
multimodal large language models (MLLMs) such as GPT-4o achieve strong
performance on VQA tasks, they frequently fall short in accessing
domain-specific or the latest knowledge. To mitigate this issue,
retrieval-augmented generation (RAG) leveraging external knowledge bases (KBs),
referred to as KB-VQA, emerges as a promising approach. Nevertheless,
conventional unimodal retrieval techniques, which translate images into textual
descriptions, often result in the loss of critical visual details. This study
presents fine-grained knowledge units, which merge textual snippets with entity
images stored in vector databases. Furthermore, we introduce a knowledge unit
retrieval-augmented generation framework (KU-RAG) that integrates fine-grained
retrieval with MLLMs. The proposed KU-RAG framework ensures precise retrieval
of relevant knowledge and enhances reasoning capabilities through a knowledge
correction chain. Experimental findings demonstrate that our approach
significantly boosts the performance of leading KB-VQA methods, achieving an
average improvement of approximately 3% and up to 11% in the best case.
