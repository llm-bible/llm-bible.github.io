---
layout: publication
title: Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection
authors: Zhu Yun, Gu Jia-chen, Sikora Caitlin, Ko Ho, Liu Yinxiao, Lin Chu-cheng, Shu Lei, Luo Liangchen, Meng Lei, Liu Bang, Chen Jindong
conference: "Arxiv"
year: 2024
bibkey: zhu2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16178"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) augmented with retrieval exhibit robust performance and extensive versatility by incorporating external contexts. However the input length grows linearly in the number of retrieved documents causing a dramatic increase in latency. In this paper we propose a novel paradigm named Sparse RAG which seeks to cut computation costs through sparsity. Specifically Sparse RAG encodes retrieved documents in parallel which eliminates latency introduced by long-range attention of retrieved documents. Then LLMs selectively decode the output by only attending to highly relevant caches auto-regressively which are chosen via prompting LLMs with special control tokens. It is notable that Sparse RAG combines the assessment of each individual document and the generation of the response into a single process. The designed sparse mechanism in a RAG system can facilitate the reduction of the number of documents loaded during decoding for accelerating the inference of the RAG system. Additionally filtering out undesirable contexts enhances the models focus on relevant context inherently improving its generation quality. Evaluation results of two datasets show that Sparse RAG can strike an optimal balance between generation quality and computational efficiency demonstrating its generalizability across both short- and long-form generation tasks.
