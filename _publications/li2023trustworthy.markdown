---
layout: publication
title: 'TRAQ: Trustworthy Retrieval Augmented Question Answering Via Conformal Prediction'
authors: Li Shuo, Park Sangdon, Lee Insup, Bastani Osbert
conference: "Arxiv"
year: 2023
bibkey: li2023trustworthy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.04642"}
  - {name: "Code", url: "https://github.com/shuoli90/TRAQ.git}{TRAQ"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG']
---
When applied to open-domain question answering, large language models (LLMs) frequently generate incorrect responses based on made-up facts, which are called \(\textit{hallucinations}\). Retrieval augmented generation (RAG) is a promising strategy to avoid hallucinations, but it does not provide guarantees on its correctness. To address this challenge, we propose the Trustworthy Retrieval Augmented Question Answering, or \(\textit{TRAQ}\), which provides the first end-to-end statistical correctness guarantee for RAG. TRAQ uses conformal prediction, a statistical technique for constructing prediction sets that are guaranteed to contain the semantically correct response with high probability. Additionally, TRAQ leverages Bayesian optimization to minimize the size of the constructed sets. In an extensive experimental evaluation, we demonstrate that TRAQ provides the desired correctness guarantee while reducing prediction set size by 16.2&#37; on average compared to an ablation. The implementation is available at \(\href{https://github.com/shuoli90/TRAQ.git}{TRAQ}\).
