---
layout: publication
title: 'Unveiling Factual Recall Behaviors Of Large Language Models Through Knowledge Neurons'
authors: Wang Yifei, Chen Yuheng, Wen Wanting, Sheng Yu, Li Linjing, Zeng Daniel Dajun
conference: "Arxiv"
year: 2024
bibkey: wang2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03247"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
In this paper we investigate whether Large Language Models (LLMs) actively recall or retrieve their internal repositories of factual knowledge when faced with reasoning tasks. Through an analysis of LLMs internal factual recall at each reasoning step via Knowledge Neurons we reveal that LLMs fail to harness the critical factual associations under certain circumstances. Instead they tend to opt for alternative shortcut-like pathways to answer reasoning questions. By manually manipulating the recall process of parametric knowledge in LLMs we demonstrate that enhancing this recall process directly improves reasoning performance whereas suppressing it leads to notable degradation. Furthermore we assess the effect of Chain-of-Thought (CoT) prompting a powerful technique for addressing complex reasoning tasks. Our findings indicate that CoT can intensify the recall of factual knowledge by encouraging LLMs to engage in orderly and reliable reasoning. Furthermore we explored how contextual conflicts affect the retrieval of facts during the reasoning process to gain a comprehensive understanding of the factual recall behaviors of LLMs. Code and data will be available soon.
