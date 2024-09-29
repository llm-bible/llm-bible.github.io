---
layout: publication
title: Think-then-Act A Dual-Angle Evaluated Retrieval-Augmented Generation
authors: Shen Yige, Jiang Hao, Qu Hua, Zhao Jihong
conference: "Arxiv"
year: 2024
bibkey: shen2024think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13050"}
tags: ['Efficiency And Optimization', 'RAG', 'Tools']
---
Despite their impressive capabilities large language models (LLMs) often face challenges such as temporal misalignment and generating hallucinatory content. Enhancing LLMs with retrieval mechanisms to fetch relevant information from external sources offers a promising solution. Inspired by the proverb Think twice before you act we propose a dual-angle evaluated retrieval-augmented generation framework . Unlike previous approaches that indiscriminately rewrite queries or perform retrieval regardless of necessity or generate temporary responses before deciding on additional retrieval which increases model generation costs our framework employs a two-phase process (i) assessing the input query for clarity and completeness to determine if rewriting is necessary; and (ii) evaluating the models capability to answer the query and deciding if additional retrieval is needed. Experimental results on five datasets show that the framework significantly improves performance. Our framework demonstrates notable improvements in accuracy and efficiency compared to existing baselines and performs well in both English and non-English contexts. Ablation studies validate the optimal model confidence threshold highlighting the resource optimization benefits of our approach.
