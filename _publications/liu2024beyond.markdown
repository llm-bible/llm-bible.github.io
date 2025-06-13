---
layout: publication
title: 'Beyond Inter-item Relations: Dynamic Adaption For Enhancing Llm-based Sequential Recommendation'
authors: Canyi Victor Liu, Wei Victor Li, Victor Youchen, Zhang, Hui Li, Rongrong Ji
conference: "Arxiv"
year: 2024
bibkey: liu2024beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.07427'}
tags: ['RecSys', 'Efficiency and Optimization', 'Applications', 'Model Architecture']
---
Sequential recommender systems (SRS) predict the next items that users may
prefer based on user historical interaction sequences. Inspired by the rise of
large language models (LLMs) in various AI applications, there is a surge of
work on LLM-based SRS. Despite their attractive performance, existing LLM-based
SRS still exhibit some limitations, including neglecting intra-item relations,
ignoring long-term collaborative knowledge and using inflexible architecture
designs for adaption. To alleviate these issues, we propose an LLM-based
sequential recommendation model named DARec. Built on top of coarse-grained
adaption for capturing inter-item relations, DARec is further enhanced with (1)
context masking that models intra-item relations to help LLM better understand
token and item semantics in the context of SRS, (2) collaborative knowledge
injection that helps LLM incorporate long-term collaborative knowledge, and (3)
a dynamic adaption mechanism that uses Bayesian optimization to flexibly choose
layer-wise adapter architectures in order to better incorporate different
sequential information. Extensive experiments demonstrate that DARec can
effectively handle sequential recommendation in a dynamic and adaptive manner.
