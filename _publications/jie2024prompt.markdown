---
layout: publication
title: 'Prompt-based Length Controlled Generation With Multiple Control Types'
authors: Jie Renlong, Meng Xiaojun, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2024
bibkey: jie2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10278"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) have attracted great attention given their
strong performance on a wide range of NLP tasks. In practice, users often
expect generated texts to fall within a specific length range, making length
controlled generation an important topic, especially for GPT-style models.
Existing length control methods mostly focus on a simple control type of "equal
to" a target length. Different from them, we propose a prompt-based method to
achieve length controlled generation under different control types with high
accuracy. In particular, we adopt reinforcement learning (RL) and sample
filtering with the reward signal given by rule-based reward models, which
enhances the length control ability of models by rewarding outputs that follow
certain control instructions. In addition, we introduce a standard prompt
extractor to parse arbitrary users' input into standard control instructions.
Experiments show that our method significantly improves the accuracy of
prompt-based length control on popular summarization datasets like CNNDM and
NYT under multiple control types. Moreover, both the standard prompt extractor
and RL-tuned model show strong generalization to unseen control prompt
templates.
