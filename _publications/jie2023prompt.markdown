---
layout: publication
title: Prompt45;based Length Controlled Generation With Reinforcement Learning
authors: Jie Renlong, Meng Xiaojun, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2023
bibkey: jie2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12030"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) like ChatGPT and GPT45;4 have attracted great attention given their surprising performance on a wide range of NLP tasks. Length controlled generation of LLMs emerges as an important topic which enables users to fully leverage the capability of LLMs in more real45;world scenarios like generating a proper answer or essay of a desired length. In addition the autoregressive generation in LLMs is extremely time45;consuming while the ability of controlling this generated length can reduce the inference cost by limiting the length. Therefore we propose a prompt45;based length control method to achieve high45;accuracy length controlled generation. In particular we adopt reinforcement learning with the reward signal given by either trainable or rule45;based reward models which further enhances the length45;control ability of LLMs by rewarding outputs that follows pre45;defined control instruction. To enable rule45;based inference we also introduce standard prompt extractor to collect the standard control information from users input. Experiments show that our method significantly improves the accuracy of prompt45;based length control for summarization task on popular datasets like CNNDM and NYT. Both the standard prompt extractor and the RL45;tuned model have show strong generalization ability to unseen control prompt templates.
