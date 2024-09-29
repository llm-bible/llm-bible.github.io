---
layout: publication
title: Mugglemath Assessing The Impact Of Query And Response Augmentation On Math Reasoning
authors: Li Chengpeng, Yuan Zheng, Yuan Hongyi, Dong Guanting, Lu Keming, Wu Jiancan, Tan Chuanqi, Wang Xiang, Zhou Chang
conference: "Arxiv"
year: 2023
bibkey: li2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05506"}
  - {name: "Code", url: "https://github.com/OFA&#45;Sys/gsm8k&#45;ScRel"}
tags: ['Has Code', 'Model Architecture']
---
In math reasoning with large language models (LLMs) fine45;tuning data augmentation by query evolution and diverse reasoning paths is empirically verified effective profoundly narrowing the gap between open45;sourced LLMs and cutting45;edge proprietary LLMs. In this paper we conduct an investigation for such data augmentation in math reasoning and are intended to answer (1) What strategies of data augmentation are more effective; (2) What is the scaling relationship between the amount of augmented data and model performance; and (3) Can data augmentation incentivize generalization to out45;of45;domain mathematical reasoning tasks To this end we create two new dataset AugGSM8K and AugMATH by complicating and diversifying the queries and sampling multiple reasoning paths from GSM8K and MATH. We obtained a series of LLMs called MuggleMath by fine45;tuning LLaMA models on AugGSM8K and AugMATH. MuggleMath substantially achieves new state45;of45;the45;art on GSM8K and MATH. A log45;linear relationship and a segmented log45;linear are presented between MuggleMaths performance and the amount of augmented data on GSM8K and MATH respectively. We also find that it is weak in out45;of45;domain math reasoning generalization from AugGSM8K to MATH and from AugMATH to GSM8K which suggests that augmenting queries that cover a broader range of subjects is more beneficial for generalization. We release our codes and augmented data in https://github.com/OFA&#45;Sys/gsm8k&#45;ScRel.
