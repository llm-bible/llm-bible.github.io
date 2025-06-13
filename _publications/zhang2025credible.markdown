---
layout: publication
title: 'Credible Plan-driven RAG Method For Multi-hop Question Answering'
authors: Ningning Zhang, Chi Zhang, Zhizhong Tan, Xingxing Yang, Weiping Deng, Wenyong Wang
conference: "Arxiv"
year: 2025
bibkey: zhang2025credible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16787'}
tags: ['RAG', 'Applications', 'Tools', 'Survey Paper']
---
Multi-hop question answering (QA) presents a considerable challenge for
Retrieval-Augmented Generation (RAG), requiring the structured decomposition of
complex queries into logical reasoning paths and the generation of dependable
intermediate results. However, deviations in reasoning paths or errors in
intermediate results, which are common in current RAG methods, may propagate
and accumulate throughout the reasoning process, diminishing the accuracy of
the answer to complex queries. To address this challenge, we propose the
Plan-then-Act-and-Review (PAR RAG) framework, which is organized into three key
stages: planning, act, and review, and aims to offer an interpretable and
incremental reasoning paradigm for accurate and reliable multi-hop question
answering by mitigating error propagation.PAR RAG initially applies a top-down
problem decomposition strategy, formulating a comprehensive plan that
integrates multiple executable steps from a holistic viewpoint. This approach
avoids the pitfalls of local optima common in traditional RAG methods, ensuring
the accuracy of the entire reasoning path. Subsequently, PAR RAG incorporates a
plan execution mechanism based on multi-granularity verification. By utilizing
both coarse-grained similarity information and fine-grained relevant data, the
framework thoroughly checks and adjusts intermediate results, ensuring process
accuracy while effectively managing error propagation and amplification.
Experimental results on multi-hop QA datasets demonstrate that the PAR RAG
framework substantially outperforms existing state-of-the-art methods in key
metrics, including EM and F1 scores.
