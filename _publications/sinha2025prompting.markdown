---
layout: publication
title: 'Don''t Retrieve, Generate: Prompting Llms For Synthetic Training Data In Dense Retrieval'
authors: Aarush Sinha
conference: "Arxiv"
year: 2025
bibkey: sinha2025prompting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21015'}
  - {name: "Code", url: 'https://huggingface.co/collections/chungimungi/arxiv-hard-negatives-68027bbc601ff6cc8eb1f449'}
tags: ['Arxiv', 'Has Code', 'Prompting', 'Training Techniques']
---
Training effective dense retrieval models often relies on hard negative (HN)
examples mined from the document corpus via methods like BM25 or cross-encoders
(CE), processes that can be computationally demanding and require full corpus
access. This paper introduces a different approach, an end-to-end pipeline
where a Large Language Model (LLM) first generates a query from a passage, and
then generates a hard negative example using *only* that query text. This
corpus-free negative generation contrasts with standard mining techniques. We
evaluated this \textsc\{LLM Query \\(\rightarrow\\) LLM HN\} approach against
traditional \textsc\{LLM Query \\(\rightarrow\\) BM25 HN\} and \textsc\{LLM Query
\\(\rightarrow\\) CE HN\} pipelines using E5-Base and GTE-Base models on several
BEIR benchmark datasets. Our results show the proposed all-LLM pipeline
achieves performance identical to both the BM25 and the computationally
intensive CE baselines across nDCG@10, Precision@10, and Recall@100 metrics.
This demonstrates that our corpus-free negative generation method matches the
effectiveness of complex, corpus-dependent mining techniques, offering a
potentially simpler and more efficient pathway for training high-performance
retrievers without sacrificing results. We make the dataset including the
queries and the hard-negatives for all three methods publicly available
https://huggingface.co/collections/chungimungi/arxiv-hard-negatives-68027bbc601ff6cc8eb1f449.
