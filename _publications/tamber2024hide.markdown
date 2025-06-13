---
layout: publication
title: 'Can''t Hide Behind The API: Stealing Black-box Commercial Embedding Models'
authors: Manveer Singh Tamber, Jasper Xian, Jimmy Lin
conference: "Arxiv"
year: 2024
bibkey: tamber2024hide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09355"}
tags: ['Training Techniques', 'Tools']
---
Embedding models that generate dense vector representations of text are
widely used and hold significant commercial value. Companies such as OpenAI and
Cohere offer proprietary embedding models via paid APIs, but despite being
"hidden" behind APIs, these models are not protected from theft. We present, to
our knowledge, the first effort to "steal" these models for retrieval by
training thief models on text-embedding pairs obtained from the APIs. Our
experiments demonstrate that it is possible to replicate the retrieval
effectiveness of commercial embedding models with a cost of under $300.
Notably, our methods allow for distilling from multiple teachers into a single
robust student model, and for distilling into presumably smaller models with
fewer dimension vectors, yet competitive retrieval effectiveness. Our findings
raise important considerations for deploying commercial embedding models and
suggest measures to mitigate the risk of model theft.
