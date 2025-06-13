---
layout: publication
title: 'Context-augmented Code Generation Using Programming Knowledge Graphs'
authors: Iman Saberi, Fatemeh Fard
conference: "Arxiv"
year: 2024
bibkey: saberi2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18251'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Pruning']
---
Large Language Models (LLMs) and Code-LLMs (CLLMs) have significantly
improved code generation, but, they frequently face difficulties when dealing
with challenging and complex problems. Retrieval-Augmented Generation (RAG)
addresses this issue by retrieving and integrating external knowledge at the
inference time. However, retrieval models often fail to find most relevant
context, and generation models, with limited context capacity, can hallucinate
when given irrelevant data. We present a novel framework that leverages a
Programming Knowledge Graph (PKG) to semantically represent and retrieve code.
This approach enables fine-grained code retrieval by focusing on the most
relevant segments while reducing irrelevant context through a tree-pruning
technique. PKG is coupled with a re-ranking mechanism to reduce even more
hallucinations by selectively integrating non-RAG solutions. We propose two
retrieval approaches-block-wise and function-wise-based on the PKG, optimizing
context granularity. Evaluations on the HumanEval and MBPP benchmarks show our
method improves pass@1 accuracy by up to 20%, and outperforms state-of-the-art
models by up to 34% on MBPP. Our contributions include PKG-based retrieval,
tree pruning to enhance retrieval precision, a re-ranking method for robust
solution selection and a Fill-in-the-Middle (FIM) enhancer module for automatic
code augmentation with relevant comments and docstrings.
