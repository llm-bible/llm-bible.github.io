---
layout: publication
title: 'Prompt-based Length Controlled Generation With Reinforcement Learning'
authors: Renlong Jie, Xiaojun Meng, Lifeng Shang, Xin Jiang, Qun Liu
conference: "Arxiv"
year: 2023
bibkey: jie2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12030"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Prompting', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) like ChatGPT and GPT-4 have attracted great
attention given their surprising performance on a wide range of NLP tasks.
Length controlled generation of LLMs emerges as an important topic, which
enables users to fully leverage the capability of LLMs in more real-world
scenarios like generating a proper answer or essay of a desired length. In
addition, the autoregressive generation in LLMs is extremely time-consuming,
while the ability of controlling this generated length can reduce the inference
cost by limiting the length. Therefore, we propose a prompt-based length
control method to achieve high-accuracy length controlled generation. In
particular, we adopt reinforcement learning with the reward signal given by
either trainable or rule-based reward models, which further enhances the
length-control ability of LLMs by rewarding outputs that follows pre-defined
control instruction. To enable rule-based inference, we also introduce standard
prompt extractor to collect the standard control information from users' input.
Experiments show that our method significantly improves the accuracy of
prompt-based length control for summarization task on popular datasets like
CNNDM and NYT. Both the standard prompt extractor and the RL-tuned model have
show strong generalization ability to unseen control prompt templates.
