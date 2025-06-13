---
layout: publication
title: 'Enronqa: Towards Personalized RAG Over Private Documents'
authors: Michael J. Ryan, Danmei Xu, Chris Nivera, Daniel Campos
conference: "Arxiv"
year: 2025
bibkey: ryan2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00263'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
Retrieval Augmented Generation (RAG) has become one of the most popular
methods for bringing knowledge-intensive context to large language models (LLM)
because of its ability to bring local context at inference time without the
cost or data leakage risks associated with fine-tuning. A clear separation of
private information from the LLM training has made RAG the basis for many
enterprise LLM workloads as it allows the company to augment LLM's
understanding using customers' private documents. Despite its popularity for
private documents in enterprise deployments, current RAG benchmarks for
validating and optimizing RAG pipelines draw their corpora from public data
such as Wikipedia or generic web pages and offer little to no personal context.
Seeking to empower more personal and private RAG we release the EnronQA
benchmark, a dataset of 103,638 emails with 528,304 question-answer pairs
across 150 different user inboxes. EnronQA enables better benchmarking of RAG
pipelines over private data and allows for experimentation on the introduction
of personalized retrieval settings over realistic data. Finally, we use EnronQA
to explore the tradeoff in memorization and retrieval when reasoning over
private documents.
