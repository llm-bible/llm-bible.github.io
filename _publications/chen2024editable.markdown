---
layout: publication
title: Editable Fairness Fine45;grained Bias Mitigation In Language Models
authors: Chen Ruizhe, Li Yichen, Yang Jianfei, Zhou Joey Tianyi, Liu Zuozhu
conference: "Arxiv"
year: 2024
bibkey: chen2024editable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11843"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness', 'RAG', 'Reinforcement Learning']
---
Generating fair and accurate predictions plays a pivotal role in deploying large language models (LLMs) in the real world. However existing debiasing methods inevitably generate unfair or incorrect predictions as they are designed and evaluated to achieve parity across different social groups but leave aside individual commonsense facts resulting in modified knowledge that elicits unreasonable or undesired predictions. In this paper we first establish a new bias mitigation benchmark BiaScope which systematically assesses performance by leveraging newly constructed datasets and metrics on knowledge retention and generalization. Then we propose a novel debiasing approach Fairness Stamp (FAST) which enables fine45;grained calibration of individual social biases. FAST identifies the decisive layer responsible for storing social biases and then calibrates its outputs by integrating a small modular network considering both bias mitigation and knowledge45;preserving demands. Comprehensive experiments demonstrate that FAST surpasses state45;of45;the45;art baselines with superior debiasing performance while not compromising the overall model capability for knowledge retention and downstream predictions. This highlights the potential of fine45;grained debiasing strategies to achieve fairness in LLMs. Code will be publicly available.
