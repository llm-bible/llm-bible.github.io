---
layout: publication
title: 'Relevance Isn''t All You Need: Scaling RAG Systems With Inference-time Compute Via Multi-criteria Reranking'
authors: Will Levine, Bijan Varjavand
conference: "Arxiv"
year: 2025
bibkey: levine2025relevance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07104"}
  - {name: "Code", url: "https://github.com/run-llama/llama_index/pull/17590"}
  - {name: "Code", url: "https://github.com/microsoft/REBEL"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting']
---
Modern Large Language Model (LLM) systems typically rely on Retrieval
Augmented Generation (RAG) which aims to gather context that is useful for
response generation. These RAG systems typically optimize strictly towards
retrieving context that is maximally relevant to the query. However,
conventional theory suggests that retrieval systems which seek to maximize
context relevance without any additional explicit criteria can create
information bottlenecks. We reaffirm this finding in the modern age of LLM's by
showing that in standard RAG pipelines, maximizing for context relevance alone
can degrade downstream response quality. In response, we show evaluations of
existing RAG methods which account for both context relevance and answer
quality. These evaluations introduce a novel finding that existing RAG systems
scale poorly with inference time compute usage when considering our combined
metric. We introduce "RErank BEyond reLevance (REBEL)", which enables RAG
systems to scale with inference-time compute via injection of multi-criteria
optimization using Chain-of-Thought prompting (and optionally Multi-Turn
dialogue). Ultimately, this enables a new performance/speed tradeoff curve,
where RAG systems are able to achieve both higher relevance of retrieved
contexts and superior answer quality as inference time increases. Code for the
implementation of our method in llama-index can be found at the following PR:
https://github.com/run-llama/llama_index/pull/17590. Code for running
experiments using this llama-index implementation can be found at
https://github.com/microsoft/REBEL.
