---
layout: publication
title: 'Supportiveness-based Knowledge Rewriting For Retrieval-augmented Language Modeling'
authors: Qiao Zile, Ye Wei, Jiang Yong, Mo Tong, Xie Pengjun, Li Weiping, Huang Fei, Zhang Shikun
conference: "Arxiv"
year: 2024
bibkey: qiao2024supportiveness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08116"}
tags: ['Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Retrieval-augmented language models (RALMs) have recently shown great
potential in mitigating the limitations of implicit knowledge in LLMs, such as
untimely updating of the latest expertise and unreliable retention of long-tail
knowledge. However, since the external knowledge base, as well as the
retriever, can not guarantee reliability, potentially leading to the knowledge
retrieved not being helpful or even misleading for LLM generation. In this
paper, we introduce Supportiveness-based Knowledge Rewriting (SKR), a robust
and pluggable knowledge rewriter inherently optimized for LLM generation.
Specifically, we introduce the novel concept of "supportiveness"--which
represents how effectively a knowledge piece facilitates downstream tasks--by
considering the perplexity impact of augmented knowledge on the response text
of a white-box LLM. Based on knowledge supportiveness, we first design a
training data curation strategy for our rewriter model, effectively identifying
and filtering out poor or irrelevant rewrites (e.g., with low supportiveness
scores) to improve data efficacy. We then introduce the direct preference
optimization (DPO) algorithm to align the generated rewrites to optimal
supportiveness, guiding the rewriter model to summarize augmented content that
better improves the final response. Comprehensive evaluations across six
popular knowledge-intensive tasks and four LLMs have demonstrated the
effectiveness and superiority of SKR. With only 7B parameters, SKR has shown
better knowledge rewriting capability over GPT-4, the current state-of-the-art
general-purpose LLM.
