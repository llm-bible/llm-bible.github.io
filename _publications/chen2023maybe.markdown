---
layout: publication
title: Maybe Only 0.5 Data is Needed A Preliminary Exploration of Low Training Data Instruction Tuning
authors: Chen Hao, Zhang Yiming, Zhang Qi, Yang Hantao, Hu Xiaomeng, Ma Xuetao, Yanggong Yifan, Zhao Junbo
conference: "Arxiv"
year: 2023
bibkey: chen2023maybe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.09246"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Instruction tuning for large language models (LLMs) has gained attention from researchers due to its ability to unlock the potential of LLMs in following instructions. While instruction tuning offers advantages for facilitating the adaptation of large language models (LLMs) to downstream tasks as a fine-tuning approach training models with tens of millions or even billions of parameters on large amounts of data results in unaffordable computational costs. To address this we focus on reducing the data used in LLM instruction tuning to decrease training costs and improve data efficiency dubbed as Low Training Data Instruction Tuning (LTD Instruction Tuning). Specifically this paper conducts a preliminary exploration into reducing the data used in LLM training and identifies several observations regarding task specialization for LLM training such as the optimization of performance for a specific task the number of instruction types required for instruction tuning and the amount of data required for task-specific models. The results suggest that task-specific models can be trained using less than 0.5 of the original dataset with a 2 improvement in performance over those trained on full task-related data.
