---
layout: publication
title: 'Refining Translations With Llms: A Constraint-aware Iterative Prompting Approach'
authors: Shangfeng Chen, Xiayang Shi, Pu Li, Yinlin Li, Jingjing Liu
conference: "Arxiv"
year: 2024
bibkey: chen2024refining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08348"}
tags: ['Applications', 'RAG', 'WMT', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable proficiency in
machine translation (MT), even without specific training on the languages in
question. However, translating rare words in low-resource or domain-specific
contexts remains challenging for LLMs. To address this issue, we propose a
multi-step prompt chain that enhances translation faithfulness by prioritizing
key terms crucial for semantic accuracy. Our method first identifies these
keywords and retrieves their translations from a bilingual dictionary,
integrating them into the LLM's context using Retrieval-Augmented Generation
(RAG). We further mitigate potential output hallucinations caused by long
prompts through an iterative self-checking mechanism, where the LLM refines its
translations based on lexical and semantic constraints. Experiments using Llama
and Qwen as base models on the FLORES-200 and WMT datasets demonstrate
significant improvements over baselines, highlighting the effectiveness of our
approach in enhancing translation faithfulness and robustness, particularly in
low-resource scenarios.
