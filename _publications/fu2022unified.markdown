---
layout: publication
title: "MIGA: A Unified Multi-task Generation Framework For Conversational Text-to-sql"
authors: Fu Yingwen, Ou Wenjie, Yu Zhou, Lin Yue
conference: "Arxiv"
year: 2022
bibkey: fu2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09278"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Conversational text-to-SQL is designed to translate multi-turn natural language questions into their corresponding SQL queries. Most state-of-the-art conversational text- to-SQL methods are incompatible with generative pre-trained language models (PLMs) such as T5. In this paper we present a two-stage unified MultI-task Generation frAmework (MIGA) that leverages PLMs ability to tackle conversational text-to-SQL. In the pre-training stage MIGA first decomposes the main task into several related sub-tasks and then unifies them into the same sequence-to-sequence (Seq2Seq) paradigm with task-specific natural language prompts to boost the main task from multi-task training. Later in the fine-tuning stage we propose four SQL perturbations to alleviate the error propagation problem. MIGA tends to achieve state-of-the-art performance on two benchmarks (SparC and CoSQL). We also provide extensive analyses and discussions to shed light on some new perspectives for conversational text-to-SQL.
