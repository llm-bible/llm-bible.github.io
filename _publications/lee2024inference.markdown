---
layout: publication
title: 'Inference Scaling For Bridging Retrieval And Augmented Generation'
authors: Youngwon Lee, Seung-won Hwang, Daniel Campos, Filip Graliński, Zhewei Yao, Yuxiong He
conference: "Arxiv"
year: 2024
bibkey: lee2024inference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10684"}
tags: ['RAG', 'Ethics and Bias']
---
Retrieval-augmented generation (RAG) has emerged as a popular approach to
steering the output of a large language model (LLM) by incorporating retrieved
contexts as inputs. However, existing work observed the generator bias, such
that improving the retrieval results may negatively affect the outcome. In this
work, we show such bias can be mitigated, from inference scaling, aggregating
inference calls from the permuted order of retrieved contexts. The proposed
Mixture-of-Intervention (MOI) explicitly models the debiased utility of each
passage with multiple forward passes to construct a new ranking. We also show
that MOI can leverage the retriever's prior knowledge to reduce the
computational cost by minimizing the number of permutations considered and
lowering the cost per LLM call. We showcase the effectiveness of MOI on diverse
RAG tasks, improving ROUGE-L on MS MARCO and EM on HotpotQA benchmarks by ~7
points.
