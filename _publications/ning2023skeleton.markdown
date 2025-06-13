---
layout: publication
title: 'Skeleton-of-thought: Prompting Llms For Efficient Parallel Generation'
authors: Xuefei Ning, Zinan Lin, Zixuan Zhou, Zifu Wang, Huazhong Yang, Yu Wang
conference: "Arxiv"
year: 2023
bibkey: ning2023skeleton
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.15337'}
tags: ['Prompting', 'Efficiency and Optimization', 'Tools']
---
This work aims at decreasing the end-to-end generation latency of large
language models (LLMs). One of the major causes of the high generation latency
is the sequential decoding approach adopted by almost all state-of-the-art
LLMs. In this work, motivated by the thinking and writing process of humans, we
propose Skeleton-of-Thought (SoT), which first guides LLMs to generate the
skeleton of the answer, and then conducts parallel API calls or batched
decoding to complete the contents of each skeleton point in parallel. Not only
does SoT provide considerable speed-ups across 12 LLMs, but it can also
potentially improve the answer quality on several question categories. SoT is
an initial attempt at data-centric optimization for inference efficiency, and
showcases the potential of eliciting high-quality answers by explicitly
planning the answer structure in language.
