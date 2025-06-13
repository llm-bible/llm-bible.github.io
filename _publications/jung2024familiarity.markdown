---
layout: publication
title: 'Familiarity-aware Evidence Compression For Retrieval-augmented Generation'
authors: Dongwon Jung, Qin Liu, Tenghao Huang, Ben Zhou, Muhao Chen
conference: "Arxiv"
year: 2024
bibkey: jung2024familiarity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12468"}
tags: ['RAG', 'Training Techniques']
---
Retrieval-augmented generation (RAG) improves large language models (LMs) by
incorporating non-parametric knowledge through evidence retrieved from external
sources. However, it often struggles to cope with inconsistent and irrelevant
information that can distract the LM from its tasks, especially when multiple
evidence pieces are required. While compressing the retrieved evidence with a
compression model aims to address this issue, the compressed evidence may still
be unfamiliar to the target model used for downstream tasks, potentially
failing to utilize the evidence effectively. We propose FaviComp
(Familarity-Aware Evidence Compression), a novel training-free evidence
compression technique that makes retrieved evidence more familiar to the target
model, while seamlessly integrating parametric knowledge from the model.
Experimental results show that FaviComp consistently outperforms most recent
evidence compression baselines across multiple open-domain QA datasets,
improving accuracy by up to 28.1% while achieving high compression rates.
Additionally, we demonstrate the effective integration of both parametric and
non-parametric knowledge during evidence compression.
