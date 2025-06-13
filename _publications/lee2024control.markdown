---
layout: publication
title: 'Control Token With Dense Passage Retrieval'
authors: Juhwan Lee, Jisu Kim
conference: "Arxiv"
year: 2024
bibkey: lee2024control
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13008"}
tags: ['Prompting', 'RAG']
---
This study addresses the hallucination problem in large language models
(LLMs). We adopted Retrieval-Augmented Generation(RAG) (Lewis et al., 2020), a
technique that involves embedding relevant information in the prompt to obtain
accurate answers. However, RAG also faced inherent issues in retrieving correct
information. To address this, we employed the Dense Passage Retrieval(DPR)
(Karpukhin et al., 2020) model for fetching domain-specific documents related
to user queries. Despite this, the DPR model still lacked accuracy in document
retrieval. We enhanced the DPR model by incorporating control tokens, achieving
significantly superior performance over the standard DPR model, with a 13%
improvement in Top-1 accuracy and a 4% improvement in Top-20 accuracy.
