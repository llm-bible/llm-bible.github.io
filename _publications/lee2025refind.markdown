---
layout: publication
title: 'REFIND At Semeval-2025 Task 3: Retrieval-augmented Factuality Hallucination Detection In Large Language Models'
authors: Donggeon Lee, Hwanjo Yu
conference: "Arxiv"
year: 2025
bibkey: lee2025refind
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13622'}
  - {name: "Code", url: 'https://github.com/oneonlee/REFIND'}
tags: ['Has Code', 'RAG', 'Security', 'Applications', 'Tools']
---
Hallucinations in large language model (LLM) outputs severely limit their
reliability in knowledge-intensive tasks such as question answering. To address
this challenge, we introduce REFIND (Retrieval-augmented Factuality
hallucINation Detection), a novel framework that detects hallucinated spans
within LLM outputs by directly leveraging retrieved documents. As part of the
REFIND, we propose the Context Sensitivity Ratio (CSR), a novel metric that
quantifies the sensitivity of LLM outputs to retrieved evidence. This
innovative approach enables REFIND to efficiently and accurately detect
hallucinations, setting it apart from existing methods. In the evaluation,
REFIND demonstrated robustness across nine languages, including low-resource
settings, and significantly outperformed baseline models, achieving superior
IoU scores in identifying hallucinated spans. This work highlights the
effectiveness of quantifying context sensitivity for hallucination detection,
thereby paving the way for more reliable and trustworthy LLM applications
across diverse languages. Our code is available at
https://github.com/oneonlee/REFIND.
