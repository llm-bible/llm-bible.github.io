---
layout: publication
title: Android In The Zoo Chain45;of45;action45;thought For GUI Agents
authors: Zhang Jiwen, Wu Jihao, Teng Yihua, Liao Minghui, Xu Nuo, Xiao Xiao, Wei Zhongyu, Tang Duyu
conference: "Arxiv"
year: 2024
bibkey: zhang2024android
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02713"}
tags: ['Agentic', 'Pretraining Methods', 'Tools']
---
Large language model (LLM) leads to a surge of autonomous GUI agents for smartphone which completes a task triggered by natural language through predicting a sequence of actions of API. Even though the task highly relies on past actions and visual observations existing studies typically consider little semantic information carried out by intermediate screenshots and screen operations. To address this this work presents Chain45;of45;Action45;Thought (dubbed CoAT) which takes the description of the previous actions the current screen and more importantly the action thinking of what actions should be performed and the outcomes led by the chosen action. We demonstrate that in a zero45;shot setting upon three off45;the45;shelf LMMs CoAT significantly improves the action prediction compared to previous proposed context modeling. To further facilitate the research in this line we construct a dataset Android45;In45;The45;Zoo (AitZ) which contains 18643 screen45;action pairs together with chain45;of45;action45;thought annotations. Experiments show that fine45;tuning a 1B model (i.e. AUTO45;UI45;base) on our AitZ dataset achieves on45;par performance with CogAgent45;Chat45;18B.
