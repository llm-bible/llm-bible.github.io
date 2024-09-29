---
layout: publication
title: Adapting Pre-trained Generative Models for Extractive Question Answering
authors: Mallick Prabir, Nayak Tapas, Bhattacharya Indrajit
conference: "Arxiv"
year: 2023
bibkey: mallick2023adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02961"}
tags: ['Applications', 'Language Modeling', 'Reinforcement Learning']
---
Pre-trained Generative models such as BART T5 etc. have gained prominence as a preferred method for text generation in various natural language processing tasks including abstractive long-form question answering (QA) and summarization. However the potential of generative models in extractive QA tasks where discriminative models are commonly employed remains largely unexplored. Discriminative models often encounter challenges associated with label sparsity particularly when only a small portion of the context contains the answer. The challenge is more pronounced for multi-span answers. In this work we introduce a novel approach that uses the power of pre-trained generative models to address extractive QA tasks by generating indexes corresponding to context tokens or sentences that form part of the answer. Through comprehensive evaluations on multiple extractive QA datasets including MultiSpanQA BioASQ MASHQA and WikiQA we demonstrate the superior performance of our proposed approach compared to existing state-of-the-art models.
