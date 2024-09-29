---
layout: publication
title: Task Contamination: Language Models May Not Be Few-shot Anymore
authors: Li Changmao, Flanigan Jeffrey
conference: "Arxiv"
year: 2023
bibkey: li2023task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.16337"}
tags: ['Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
Large language models (LLMs) offer impressive performance in various zero-shot and few-shot tasks. However their success in zero-shot and few-shot settings may be affected by task contamination a potential limitation that has not been thoroughly examined. This paper investigates how zero-shot and few-shot performance of LLMs has changed chronologically over time. Utilizing GPT-3 series models and several other recent open-sourced LLMs and controlling for dataset difficulty we find that on datasets released before the LLM training data creation date LLMs perform surprisingly better than on datasets released after. This strongly indicates that for many LLMs there exists task contamination on zero-shot and few-shot evaluation for datasets released prior to the LLMs training data creation date. Additionally we utilize training data inspection task example extraction and a membership inference attack which reveal further evidence of task contamination. Importantly we find that for classification tasks with no possibility of task contamination LLMs rarely demonstrate statistically significant improvements over simple majority baselines in both zero and few-shot settings.
