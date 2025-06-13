---
layout: publication
title: 'Hybrid Retrieval For Hallucination Mitigation In Large Language Models: A Comparative Analysis'
authors: Chandana Sree Mala, Gizem Gezici, Fosca Giannotti
conference: "Arxiv"
year: 2025
bibkey: mala2025hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05324"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) excel in language comprehension and generation
but are prone to hallucinations, producing factually incorrect or unsupported
outputs. Retrieval Augmented Generation (RAG) systems address this issue by
grounding LLM responses with external knowledge. This study evaluates the
relationship between retriever effectiveness and hallucination reduction in
LLMs using three retrieval approaches: sparse retrieval based on BM25 keyword
search, dense retrieval using semantic search with Sentence Transformers, and a
proposed hybrid retrieval module. The hybrid module incorporates query
expansion and combines the results of sparse and dense retrievers through a
dynamically weighted Reciprocal Rank Fusion score. Using the HaluBench dataset,
a benchmark for hallucinations in question answering tasks, we assess retrieval
performance with metrics such as mean average precision and normalised
discounted cumulative gain, focusing on the relevance of the top three
retrieved documents. Results show that the hybrid retriever achieves better
relevance scores, outperforming both sparse and dense retrievers. Further
evaluation of LLM-generated answers against ground truth using metrics such as
accuracy, hallucination rate, and rejection rate reveals that the hybrid
retriever achieves the highest accuracy on fails, the lowest hallucination
rate, and the lowest rejection rate. These findings highlight the hybrid
retriever's ability to enhance retrieval relevance, reduce hallucination rates,
and improve LLM reliability, emphasising the importance of advanced retrieval
techniques in mitigating hallucinations and improving response accuracy.
