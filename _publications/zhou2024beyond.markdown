---
layout: publication
title: 'Beyond Content Relevance: Evaluating Instruction Following In Retrieval Models'
authors: Jianqun Zhou, Yuanlei Zheng, Wei Chen, Qianqian Zheng, Hui Su, Wei Zhang, Rui Meng, Xiaoyu Shen
conference: "Arxiv"
year: 2024
bibkey: zhou2024beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.23841'}
tags: ['Fine-Tuning', 'Prompting', 'Training Techniques', 'Pretraining Methods']
---
Instruction-following capabilities in LLMs have progressed significantly,
enabling more complex user interactions through detailed prompts. However,
retrieval systems have not matched these advances, most of them still relies on
traditional lexical and semantic matching techniques that fail to fully capture
user intent. Recent efforts have introduced instruction-aware retrieval models,
but these primarily focus on intrinsic content relevance, which neglects the
importance of customized preferences for broader document-level attributes.
This study evaluates the instruction-following capabilities of various
retrieval models beyond content relevance, including LLM-based dense retrieval
and reranking models. We develop InfoSearch, a novel retrieval evaluation
benchmark spanning six document-level attributes: Audience, Keyword, Format,
Language, Length, and Source, and introduce novel metrics -- Strict Instruction
Compliance Ratio (SICR) and Weighted Instruction Sensitivity Evaluation (WISE)
to accurately assess the models' responsiveness to instructions. Our findings
indicate that although fine-tuning models on instruction-aware retrieval
datasets and increasing model size enhance performance, most models still fall
short of instruction compliance.
