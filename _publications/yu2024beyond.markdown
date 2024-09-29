---
layout: publication
title: BEYOND DIALOGUE A Profile45;dialogue Alignment Framework Towards General Role45;playing Language Model
authors: Yu Yeyong, Yu Runsheng, Wei Haojie, Zhang Zhanqiu, Qian Quan
conference: "Arxiv"
year: 2024
bibkey: yu2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10903"}
  - {name: "Code", url: "https://github.com/yuyouyu32/BeyondDialogue"}
tags: ['Ethics And Bias', 'Has Code', 'Prompting', 'Tools', 'Training Techniques']
---
The rapid advancement of large language models (LLMs) has revolutionized role45;playing enabling the development of general role45;playing models. However current role45;playing training has two significant issues (I) Using a predefined role profile to prompt dialogue training for specific scenarios usually leads to inconsistencies and even conflicts between the dialogue and the profile resulting in training biases. (II) The model learns to imitate the role based solely on the profile neglecting profile45;dialogue alignment at the sentence level. In this work we propose a simple yet effective framework called BEYOND DIALOGUE designed to overcome these hurdles. This framework innovatively introduces beyond dialogue tasks to align dialogue with profile traits based on each specific scenario thereby eliminating biases during training. Furthermore by adopting an innovative prompting mechanism that generates reasoning outcomes for training the framework allows the model to achieve fine45;grained alignment between profile and dialogue at the sentence level. The aforementioned methods are fully automated and low45;cost. Additionally the integration of automated dialogue and objective evaluation methods forms a comprehensive framework paving the way for general role45;playing. Experimental results demonstrate that our model excels in adhering to and reflecting various dimensions of role profiles outperforming most proprietary general and specialized role45;playing baselines. All code and datasets are available at https://github.com/yuyouyu32/BeyondDialogue.
