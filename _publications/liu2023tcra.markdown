---
layout: publication
title: 'TCRA-LLM: Token Compression Retrieval Augmented Large Language Model For Inference Cost Reduction'
authors: Junyi Liu, Liangzhi Li, Tong Xiang, Bowen Wang, Yiming Qian
conference: "Arxiv"
year: 2023
bibkey: liu2023tcra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15556"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Prompting', 'In-Context Learning']
---
Since ChatGPT released its API for public use, the number of applications
built on top of commercial large language models (LLMs) increase exponentially.
One popular usage of such models is leveraging its in-context learning ability
and generating responses given user queries leveraging knowledge obtained by
retrieval augmentation. One problem of deploying commercial retrieval-augmented
LLMs is the cost due to the additionally retrieved context that largely
increases the input token size of the LLMs. To mitigate this, we propose a
token compression scheme that includes two methods: summarization compression
and semantic compression. The first method applies a T5-based model that is
fine-tuned by datasets generated using self-instruct containing samples with
varying lengths and reduce token size by doing summarization. The second method
further compresses the token size by removing words with lower impact on the
semantic. In order to adequately evaluate the effectiveness of the proposed
methods, we propose and utilize a dataset called Food-Recommendation DB (FRDB)
focusing on food recommendation for women around pregnancy period or infants.
Our summarization compression can reduce 65% of the retrieval token size with
further 0.3% improvement on the accuracy; semantic compression provides a more
flexible way to trade-off the token size with performance, for which we can
reduce the token size by 20% with only 1.6% of accuracy drop.
