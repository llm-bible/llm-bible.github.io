---
layout: publication
title: "Auto-instruct: Automatic Instruction Generation And Ranking For Black-box Language Models"
authors: Zhang Zhihan, Wang Shuohang, Yu Wenhao, Xu Yichong, Iter Dan, Zeng Qingkai, Liu Yang, Zhu Chenguang, Jiang Meng
conference: "Arxiv"
year: 2023
bibkey: zhang2023auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13127"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) can perform a wide range of tasks by following natural language instructions without the necessity of task-specific fine-tuning. Unfortunately the performance of LLMs is greatly influenced by the quality of these instructions and manually writing effective instructions for each task is a laborious and subjective process. In this paper we introduce Auto-Instruct a novel method to automatically improve the quality of instructions provided to LLMs. Our method leverages the inherent generative ability of LLMs to produce diverse candidate instructions for a given task and then ranks them using a scoring model trained on a variety of 575 existing NLP tasks. In experiments on 118 out-of-domain tasks Auto-Instruct surpasses both human-written instructions and existing baselines of LLM-generated instructions. Furthermore our method exhibits notable generalizability even with other LLMs that are not incorporated into its training process.
