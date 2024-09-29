---
layout: publication
title: Selective Self45;rehearsal A Fine45;tuning Approach To Improve Generalization In Large Language Models
authors: Gupta Sonam, Nandwani Yatin, Yehudai Asaf, Mishra Mayank, Pandey Gaurav, Raghu Dinesh, Joshi Sachindra
conference: "Arxiv"
year: 2024
bibkey: gupta2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04787"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Fine45;tuning Large Language Models (LLMs) on specific datasets is a common practice to improve performance on target tasks. However this performance gain often leads to overfitting where the model becomes too specialized in either the task or the characteristics of the training data resulting in a loss of generalization. This paper introduces Selective Self45;Rehearsal (SSR) a fine45;tuning approach that achieves performance comparable to the standard supervised fine45;tuning (SFT) while improving generalization. SSR leverages the fact that there can be multiple valid responses to a query. By utilizing the models correct responses SSR reduces model specialization during the fine45;tuning stage. SSR first identifies the correct model responses from the training set by deploying an appropriate LLM as a judge. Then it fine45;tunes the model using the correct model responses and the gold response for the remaining samples. The effectiveness of SSR is demonstrated through experiments on the task of identifying unanswerable queries across various datasets. The results show that standard SFT can lead to an average performance drop of up to 16.737; on multiple benchmarks such as MMLU and TruthfulQA. In contrast SSR results in close to 237; drop on average indicating better generalization capabilities compared to standard SFT.
