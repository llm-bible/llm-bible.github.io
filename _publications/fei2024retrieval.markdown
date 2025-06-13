---
layout: publication
title: 'Retrieval Meets Reasoning: Dynamic In-context Editing For Long-text Understanding'
authors: Weizhi Fei, Xueyan Niu, Guoqing Xie, Yanhua Zhang, Bo Bai, Lei Deng, Wei Han
conference: "Arxiv"
year: 2024
bibkey: fei2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12331"}
tags: ['RAG', 'Training Techniques']
---
Current Large Language Models (LLMs) face inherent limitations due to their
pre-defined context lengths, which impede their capacity for multi-hop
reasoning within extensive textual contexts. While existing techniques like
Retrieval-Augmented Generation (RAG) have attempted to bridge this gap by
sourcing external information, they fall short when direct answers are not
readily available. We introduce a novel approach that re-imagines information
retrieval through dynamic in-context editing, inspired by recent breakthroughs
in knowledge editing. By treating lengthy contexts as malleable external
knowledge, our method interactively gathers and integrates relevant
information, thereby enabling LLMs to perform sophisticated reasoning steps.
Experimental results demonstrate that our method effectively empowers
context-limited LLMs, such as Llama2, to engage in multi-hop reasoning with
improved performance, which outperforms state-of-the-art context window
extrapolation methods and even compares favorably to more advanced commercial
long-context models. Our interactive method not only enhances reasoning
capabilities but also mitigates the associated training and computational
costs, making it a pragmatic solution for enhancing LLMs' reasoning within
expansive contexts.
