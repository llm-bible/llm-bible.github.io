---
layout: publication
title: "Instupr : Instruction-based Unsupervised Passage Reranking With Large Language Models"
authors: Huang Chao-wei, Chen Yun-nung
conference: "Arxiv"
year: 2024
bibkey: huang2024instupr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16435"}
  - {name: "Code", url: "https://github.com/MiuLab/InstUPR"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
This paper introduces InstUPR an unsupervised passage reranking method based on large language models (LLMs). Different from existing approaches that rely on extensive training with query-document pairs or retrieval-specific instructions our method leverages the instruction-following capabilities of instruction-tuned LLMs for passage reranking without any additional fine-tuning. To achieve this we introduce a soft score aggregation technique and employ pairwise reranking for unsupervised passage reranking. Experiments on the BEIR benchmark demonstrate that InstUPR outperforms unsupervised baselines as well as an instruction-tuned reranker highlighting its effectiveness and superiority. Source code to reproduce all experiments is open-sourced at https://github.com/MiuLab/InstUPR"
