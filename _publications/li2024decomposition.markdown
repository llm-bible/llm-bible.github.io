---
layout: publication
title: 'Dotamath: Decomposition Of Thought With Code Assistance And Self-correction For Mathematical Reasoning'
authors: Chengpeng Li, Guanting Dong, Mingfeng Xue, Ru Peng, Xiang Wang, Dayiheng Liu
conference: "Arxiv"
year: 2024
bibkey: li2024decomposition
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04078"}
  - {name: "Code", url: "https://github.com/ChengpengLi1003/DotaMath"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have made impressive progress in handling simple
math problems, yet they still struggle with more challenging and complex
mathematical tasks. In this paper, we introduce a series of LLMs that employs
the Decomposition of thought with code assistance and self-correction for
mathematical reasoning, dubbed as DotaMath. DotaMath models tackle complex
mathematical tasks by decomposing them into simpler logical subtasks,
leveraging code to solve these subtasks, obtaining fine-grained feedback from
the code interpreter, and engaging in self-reflection and correction. By
annotating diverse interactive tool-use trajectories and employing query
evolution on GSM8K and MATH datasets, we generate an instruction fine-tuning
dataset called DotaMathQA with 574K query-response pairs. We train a series of
base LLMs using imitation learning on DotaMathQA, resulting in DotaMath models
that achieve remarkable performance compared to open-source LLMs across various
in-domain and out-of-domain benchmarks. Notably, DotaMath-deepseek-7B showcases
an outstanding performance of 64.8% on the competitive MATH dataset and 86.7%
on GSM8K. Besides, DotaMath-deepseek-7B maintains strong competitiveness on a
series of in-domain and out-of-domain benchmarks (Avg. 80.1%). Looking forward,
we anticipate that the DotaMath paradigm will open new pathways for addressing
intricate mathematical problems. Our code is publicly available at
https://github.com/ChengpengLi1003/DotaMath.
