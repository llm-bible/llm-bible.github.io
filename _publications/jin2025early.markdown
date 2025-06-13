---
layout: publication
title: 'END: Early Noise Dropping For Efficient And Effective Context Denoising'
authors: Hongye Jin, Pei Chen, Jingfeng Yang, Zhengyang Wang, Meng Jiang, Yifan Gao, Binxuan Huang, Xinyang Zhang, Zheng Li, Tianyi Liu, Huasheng Li, Bing Yin
conference: "Arxiv"
year: 2025
bibkey: jin2025early
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18915"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated remarkable performance across
a wide range of natural language processing tasks. However, they are often
distracted by irrelevant or noisy context in input sequences that degrades
output quality. This problem affects both long- and short-context scenarios,
such as retrieval-augmented generation, table question-answering, and
in-context learning. We reveal that LLMs can implicitly identify whether input
sequences contain useful information at early layers, prior to token
generation. Leveraging this insight, we introduce Early Noise Dropping
(\textsc\{END\}), a novel approach to mitigate this issue without requiring
fine-tuning the LLMs. \textsc\{END\} segments input sequences into chunks and
employs a linear prober on the early layers of LLMs to differentiate between
informative and noisy chunks. By discarding noisy chunks early in the process,
\textsc\{END\} preserves critical information, reduces distraction, and lowers
computational overhead. Extensive experiments demonstrate that \textsc\{END\}
significantly improves both performance and efficiency across different LLMs on
multiple evaluation datasets. Furthermore, by investigating LLMs' implicit
understanding to the input with the prober, this work also deepens
understanding of how LLMs do reasoning with contexts internally.
