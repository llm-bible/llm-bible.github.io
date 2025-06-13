---
layout: publication
title: 'Query-opt: Optimizing Inference Of Large Language Models Via Multi-query Instructions In Meeting Summarization'
authors: Md Tahmid Rahman Laskar, Elena Khasanova, Xue-yong Fu, Cheng Chen, Shashi Bhushan Tn
conference: "Arxiv"
year: 2024
bibkey: laskar2024query
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.00067'}
tags: ['GPT', 'Tools', 'Applications', 'Prompting', 'Model Architecture', 'Reinforcement Learning']
---
This work focuses on the task of query-based meeting summarization in which
the summary of a context (meeting transcript) is generated in response to a
specific query. When using Large Language Models (LLMs) for this task, usually
a new call to the LLM inference endpoint/API is triggered for each new query,
even if the context stays the same. However, repeated calls to the LLM
inference endpoints would significantly increase the costs of using them in
production, making LLMs impractical for many real-world use cases. To address
this problem, in this paper, we investigate whether combining the queries for
the same input context in a single prompt to minimize repeated calls can be
successfully used in meeting summarization. In this regard, we conduct
extensive experiments by comparing the performance of various popular LLMs:
GPT-4, Gemini, Claude-3, LLaMA-2, Mistral, Phi-3, and Qwen-2 in single-query
and multi-query settings. We observe that 100% reliability in generating the
response in the expected format is usually limited to certain closed-source
LLMs, with most open-source LLMs lagging behind (except a few 7B parameters
LLMs like Mistral and Phi-3). We conclude that multi-query prompting could be
useful to significantly optimize the inference costs in meeting summarization.
