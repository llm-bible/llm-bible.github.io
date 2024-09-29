---
layout: publication
title: Instupr Instruction45;based Unsupervised Passage Reranking With Large Language Models
authors: Huang Chao-wei, Chen Yun-nung
conference: "Arxiv"
year: 2024
bibkey: huang2024instupr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16435"}
  - {name: "Code", url: "https://github.com/MiuLab/InstUPR"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
This paper introduces InstUPR an unsupervised passage reranking method based on large language models (LLMs). Different from existing approaches that rely on extensive training with query45;document pairs or retrieval45;specific instructions our method leverages the instruction45;following capabilities of instruction45;tuned LLMs for passage reranking without any additional fine45;tuning. To achieve this we introduce a soft score aggregation technique and employ pairwise reranking for unsupervised passage reranking. Experiments on the BEIR benchmark demonstrate that InstUPR outperforms unsupervised baselines as well as an instruction45;tuned reranker highlighting its effectiveness and superiority. Source code to reproduce all experiments is open45;sourced at https://github.com/MiuLab/InstUPR
