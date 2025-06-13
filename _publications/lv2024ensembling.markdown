---
layout: publication
title: 'Specfuse: Ensembling Large Language Models Via Next-segment Prediction'
authors: Bo Lv, Chen Tang, Yanan Zhang, Xin Liu, Yue Yu, Ping Luo
conference: "Arxiv"
year: 2024
bibkey: lv2024ensembling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07380"}
tags: ['Training Techniques', 'RAG', 'Tools', 'Merging']
---
Ensembles of generative large language models (LLMs) can integrate the
strengths of different LLMs to compensate for the limitations of individual
models. However, recent work has focused on training an additional fusion model
to combine complete responses from multiple LLMs, failing to tap into their
collaborative potential to generate higher-quality responses. Moreover, as the
additional fusion model is trained on a specialized dataset, these methods
struggle with generalizing to open-domain queries from online users. In this
paper, we propose SpecFuse, a novel ensemble framework that outputs the fused
result by iteratively producing the next segment through collaboration among
LLMs. This is achieved through cyclic execution of its inference and
verification components. In each round, the inference component invokes each
base LLM to generate candidate segments in parallel, and the verify component
calls these LLMs again to predict the ranking of the segments. The top-ranked
segment is then broadcast to all LLMs, encouraging them to generate
higher-quality segments in the next round. This approach also allows the base
LLMs to be plug-and-play, without any training or adaptation, avoiding
generalization limitations. Furthermore, to conserve computational resources,
we propose a model exit mechanism that dynamically excludes models exhibiting
poor performance in previous rounds during each query response. In this way, it
effectively reduces the number of model calls while maintaining overall
performance.
