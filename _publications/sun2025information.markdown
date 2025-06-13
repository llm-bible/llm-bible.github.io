---
layout: publication
title: 'Information Gain-guided Causal Intervention For Autonomous Debiasing Large Language Models'
authors: Zhouhao Sun, Xiao Ding, Li Du, Yunpeng Xu, Yixuan Ma, Yang Zhao, Bing Qin, Ting Liu
conference: "Arxiv"
year: 2025
bibkey: sun2025information
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12898'}
tags: ['Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Ethics and Bias', 'In-Context Learning', 'Pretraining Methods']
---
Despite significant progress, recent studies indicate that current large language models (LLMs) may still capture dataset biases and utilize them during inference, leading to the poor generalizability of LLMs. However, due to the diversity of dataset biases and the insufficient nature of bias suppression based on in-context learning, the effectiveness of previous prior knowledge-based debiasing methods and in-context learning based automatic debiasing methods is limited. To address these challenges, we explore the combination of causal mechanisms with information theory and propose an information gain-guided causal intervention debiasing (ICD) framework. To eliminate biases within the instruction-tuning dataset, it is essential to ensure that these biases do not provide any additional information to predict the answers, i.e., the information gain of these biases for predicting the answers needs to be 0. Under this guidance, this framework utilizes a causal intervention-based data rewriting method to automatically and autonomously balance the distribution of instruction-tuning dataset for reducing the information gain. Subsequently, it employs a standard supervised fine-tuning process to train LLMs on the debiased dataset. Experimental results show that ICD can effectively debias LLM to improve its generalizability across different tasks.
