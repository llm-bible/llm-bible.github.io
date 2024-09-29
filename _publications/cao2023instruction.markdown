---
layout: publication
title: 'Instruction Mining: Instruction Data Selection For Tuning Large Language Models'
authors: Cao Yihan, Kang Yanbin, Wang Chi, Sun Lichao
conference: "Arxiv"
year: 2023
bibkey: cao2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.06290"}
tags: ['Pretraining Methods', 'RAG']
---
Large language models (LLMs) are initially pretrained for broad capabilities and then finetuned with instruction-following datasets to improve their performance in interacting with humans. Despite advances in finetuning a standardized guideline for selecting high-quality datasets to optimize this process remains elusive. In this paper we first propose InstructMining an innovative method designed for automatically selecting premium instruction-following data for finetuning LLMs. Specifically InstructMining utilizes natural language indicators as a measure of data quality applying them to evaluate unseen datasets. During experimentation we discover that double descent phenomenon exists in large language model finetuning. Based on this observation we further leverage BlendSearch to help find the best subset among the entire dataset (i.e. 2532 out of 100000). Experiment results show that InstructMining-7B achieves state-of-the-art performance on two of the most popular benchmarks LLM-as-a-judge and Huggingface OpenLLM leaderboard.
