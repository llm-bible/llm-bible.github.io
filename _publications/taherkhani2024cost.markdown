---
layout: publication
title: 'Epic: Cost-effective Search-based Prompt Engineering Of Llms For Code Generation'
authors: Hamed Taherkhani, Melika Sepindband, Hung Viet Pham, Song Wang, Hadi Hemmati
conference: "Arxiv"
year: 2024
bibkey: taherkhani2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11198"}
tags: ['RAG', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have seen increasing use in various software
development tasks, especially in code generation. The most advanced recent
methods attempt to incorporate feedback from code execution into prompts to
help guide LLMs in generating correct code, in an iterative process. While
effective, these methods could be costly and time-consuming due to numerous
interactions with the LLM and the extensive token usage. To address this issue,
we propose an alternative approach named Evolutionary Prompt Engineering for
Code (EPiC), which leverages a lightweight evolutionary algorithm to evolve the
original prompts toward better ones that produce high-quality code, with
minimal interactions with LLM. Our evaluation against state-of-the-art (SOTA)
LLM-based code generation models shows that EPiC outperforms all the baselines
in terms of cost-effectiveness.
