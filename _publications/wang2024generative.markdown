---
layout: publication
title: 'Generative Retrieval With Large Language Models'
authors: Ye Wang, Xinrun Xu, Rui Xie, Wenxin Hu, Wei Ye
conference: "Arxiv"
year: 2024
bibkey: wang2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17010"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Prompting', 'Pre-Training']
---
When completing knowledge-intensive tasks, humans sometimes need not just an
answer but also a corresponding reference passage for auxiliary reading.
Previous methods required obtaining pre-segmented article chunks through
additional retrieval models. This paper explores leveraging the parameterized
knowledge stored during the pre-training phase of large language models (LLMs)
to independently recall reference passage from any starting position. We
propose a two-stage framework that simulates the scenario of humans recalling
easily forgotten references. Initially, the LLM is prompted to recall document
title identifiers to obtain a coarse-grained document set. Then, based on the
acquired coarse-grained document set, it recalls fine-grained passage. In the
two-stage recall process, we use constrained decoding to ensure that content
outside of the stored documents is not generated. To increase speed, we only
recall a short prefix in the second stage, then locate its position to retrieve
a complete passage. Experiments on KILT knowledge-sensitive tasks have verified
that LLMs can independently recall reference passage location in various task
forms, and the obtained reference significantly assist downstream tasks.
