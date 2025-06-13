---
layout: publication
title: 'Coderag-bench: Can Retrieval Augment Code Generation?'
authors: Zora Zhiruo Wang, Akari Asai, Xinyan Velocity Yu, Frank F. Xu, Yiqing Xie, Graham Neubig, Daniel Fried
conference: "Arxiv"
year: 2024
bibkey: wang2024coderag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14497"}
tags: ['RAG', 'Tools', 'Applications', 'Reinforcement Learning']
---
While language models (LMs) have proven remarkably adept at generating code,
many programs are challenging for LMs to generate using their parametric
knowledge alone. Providing external contexts such as library documentation can
facilitate generating accurate and functional code. Despite the success of
retrieval-augmented generation (RAG) in various text-oriented tasks, its
potential for improving code generation remains under-explored. In this work,
we conduct a systematic, large-scale analysis by asking: in what scenarios can
retrieval benefit code generation models? and what challenges remain? We first
curate a comprehensive evaluation benchmark, CodeRAG-Bench, encompassing three
categories of code generation tasks, including basic programming, open-domain,
and repository-level problems. We aggregate documents from five sources for
models to retrieve contexts: competition solutions, online tutorials, library
documentation, StackOverflow posts, and GitHub repositories. We examine
top-performing models on CodeRAG-Bench by providing contexts retrieved from one
or multiple sources. While notable gains are made in final code generation by
retrieving high-quality contexts across various settings, our analysis reveals
room for improvement -- current retrievers still struggle to fetch useful
contexts especially with limited lexical overlap, and generators fail to
improve with limited context lengths or abilities to integrate additional
contexts. We hope CodeRAG-Bench serves as an effective testbed to encourage
further development of advanced code-oriented RAG methods.
