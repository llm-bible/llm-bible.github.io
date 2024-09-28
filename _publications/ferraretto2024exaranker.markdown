---
layout: publication
title: ExaRanker-Open Synthetic Explanation for IR using Open-Source LLMs
authors: Ferraretto Fernando, Laitz Thiago, Lotufo Roberto, Nogueira Rodrigo
conference: "Arxiv"
year: 2024
bibkey: ferraretto2024exaranker
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06334"}
  - {name: "Code", url: "https://github.com/unicamp-dl/ExaRanker"}
tags: ['ARXIV', 'Applications', 'GPT', 'Has Code', 'Interpretability And Interpretability', 'LLM', 'RAG', 'Training Techniques']
---
ExaRanker recently introduced an approach to training information retrieval (IR) models incorporating natural language explanations as additional labels. The method addresses the challenge of limited labeled examples leading to improvements in the effectiveness of IR models. However the initial results were based on proprietary language models such as GPT-3.5 which posed constraints on dataset size due to its cost and data privacy. In this paper we introduce ExaRanker-Open where we adapt and explore the use of open-source language models to generate explanations. The method has been tested using different LLMs and datasets sizes to better comprehend the effective contribution of data augmentation. Our findings reveal that incorporating explanations consistently enhances neural rankers with benefits escalating as the LLM size increases. Notably the data augmentation method proves advantageous even with large datasets as evidenced by ExaRanker surpassing the target baseline by 0.6 nDCG@10 points in our study. To encourage further advancements by the research community we have open-sourced both the code and datasets at https://github.com/unicamp-dl/ExaRanker.
