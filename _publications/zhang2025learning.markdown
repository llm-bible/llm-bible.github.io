---
layout: publication
title: 'Learning To Select In-context Demonstration Preferred By Large Language Model'
authors: Zheng Zhang, Shaocheng Lan, Lei Song, Jiang Bian, Yexin Li, Kan Ren
conference: "Arxiv"
year: 2025
bibkey: zhang2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19966"}
tags: ['RAG', 'Tools', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) enables large language models (LLMs) to adapt to new tasks during inference using only a few demonstrations. However, ICL performance is highly dependent on the selection of these demonstrations. Recent work explores retrieval-based methods for selecting query-specific demonstrations, but these approaches often rely on surrogate objectives such as metric learning, failing to directly optimize ICL performance. Consequently, they struggle to identify truly beneficial demonstrations. Moreover, their discriminative retrieval paradigm is ineffective when the candidate pool lacks sufficient high-quality demonstrations. To address these challenges, we propose GenICL, a novel generative preference learning framework that leverages LLM feedback to directly optimize demonstration selection for ICL. Experiments on 19 datasets across 11 task categories demonstrate that GenICL achieves superior performance than existing methods in selecting the most effective demonstrations, leading to better ICL performance.
