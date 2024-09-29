---
layout: publication
title: MIGA A Unified Multi45;task Generation Framework For Conversational Text45;to45;sql
authors: Fu Yingwen, Ou Wenjie, Yu Zhou, Lin Yue
conference: "Arxiv"
year: 2022
bibkey: fu2022unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09278"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Conversational text45;to45;SQL is designed to translate multi45;turn natural language questions into their corresponding SQL queries. Most state45;of45;the45;art conversational text45; to45;SQL methods are incompatible with generative pre45;trained language models (PLMs) such as T5. In this paper we present a two45;stage unified MultI45;task Generation frAmework (MIGA) that leverages PLMs ability to tackle conversational text45;to45;SQL. In the pre45;training stage MIGA first decomposes the main task into several related sub45;tasks and then unifies them into the same sequence45;to45;sequence (Seq2Seq) paradigm with task45;specific natural language prompts to boost the main task from multi45;task training. Later in the fine45;tuning stage we propose four SQL perturbations to alleviate the error propagation problem. MIGA tends to achieve state45;of45;the45;art performance on two benchmarks (SparC and CoSQL). We also provide extensive analyses and discussions to shed light on some new perspectives for conversational text45;to45;SQL.
