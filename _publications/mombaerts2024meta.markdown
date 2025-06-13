---
layout: publication
title: 'Meta Knowledge For Retrieval Augmented Large Language Models'
authors: Laurent Mombaerts, Terry Ding, Adi Banerjee, Florian Felice, Jonathan Taws, Tarik Borogovac
conference: "Arxiv"
year: 2024
bibkey: mombaerts2024meta
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.09017'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Retrieval Augmented Generation (RAG) is a technique used to augment Large
Language Models (LLMs) with contextually relevant, time-critical, or
domain-specific information without altering the underlying model parameters.
However, constructing RAG systems that can effectively synthesize information
from large and diverse set of documents remains a significant challenge. We
introduce a novel data-centric RAG workflow for LLMs, transforming the
traditional retrieve-then-read system into a more advanced
prepare-then-rewrite-then-retrieve-then-read framework, to achieve higher
domain expert-level understanding of the knowledge base. Our methodology relies
on generating metadata and synthetic Questions and Answers (QA) for each
document, as well as introducing the new concept of Meta Knowledge Summary (MK
Summary) for metadata-based clusters of documents. The proposed innovations
enable personalized user-query augmentation and in-depth information retrieval
across the knowledge base. Our research makes two significant contributions:
using LLMs as evaluators and employing new comparative performance metrics, we
demonstrate that (1) using augmented queries with synthetic question matching
significantly outperforms traditional RAG pipelines that rely on document
chunking (p < 0.01), and (2) meta knowledge-augmented queries additionally
significantly improve retrieval precision and recall, as well as the final
answers breadth, depth, relevancy, and specificity. Our methodology is
cost-effective, costing less than $20 per 2000 research papers using Claude 3
Haiku, and can be adapted with any fine-tuning of either the language or
embedding models to further enhance the performance of end-to-end RAG
pipelines.
