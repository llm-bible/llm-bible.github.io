---
layout: publication
title: 'Investigating Hallucinations In Pruned Large Language Models For Abstractive Summarization'
authors: Chrysostomou George, Zhao Zhixue, Williams Miles, Aletras Nikolaos
conference: "Arxiv"
year: 2023
bibkey: chrysostomou2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09335"}
tags: ['Applications', 'Efficiency And Optimization', 'Pruning', 'Reinforcement Learning', 'Responsible AI']
---
Despite the remarkable performance of generative large language models (LLMs) on abstractive summarization, they face two significant challenges: their considerable size and tendency to hallucinate. Hallucinations are concerning because they erode reliability and raise safety issues. Pruning is a technique that reduces model size by removing redundant weights, enabling more efficient sparse inference. Pruned models yield downstream task performance comparable to the original, making them ideal alternatives when operating on a limited budget. However, the effect that pruning has upon hallucinations in abstractive summarization with LLMs has yet to be explored. In this paper, we provide an extensive empirical study across five summarization datasets, two state-of-the-art pruning methods, and five instruction-tuned LLMs. Surprisingly, we find that hallucinations from pruned LLMs are less prevalent than the original models. Our analysis suggests that pruned models tend to depend more on the source document for summary generation. This leads to a higher lexical overlap between the generated summary and the source document, which could be a reason for the reduction in hallucination risk.
