---
layout: publication
title: 'Skywork-math: Data Scaling Laws For Mathematical Reasoning In Large Language Models -- The Story Goes On'
authors: Zeng Liang, Zhong Liangjun, Zhao Liang, Wei Tianwen, Yang Liu, He Jujie, Cheng Cheng, Hu Rui, Liu Yang, Yan Shuicheng, Fang Han, Zhou Yahui
conference: "Arxiv"
year: 2024
bibkey: zeng2024skywork
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08348"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Scaling Laws']
---
In this paper, we investigate the underlying factors that potentially enhance the mathematical reasoning capabilities of large language models (LLMs). We argue that the data scaling law for math reasoning capabilities in modern LLMs is far from being saturated, highlighting how the model's quality improves with increases in data quantity. To support this claim, we introduce the Skywork-Math model series, supervised fine-tuned (SFT) on common 7B LLMs using our proposed 2.5M-instance Skywork-MathQA dataset. Skywork-Math 7B has achieved impressive accuracies of 51.2&#37; on the competition-level MATH benchmark and 83.9&#37; on the GSM8K benchmark using only SFT data, outperforming an early version of GPT-4 on MATH. The superior performance of Skywork-Math models contributes to our novel two-stage data synthesis and model SFT pipelines, which include three different augmentation methods and a diverse seed problem set, ensuring both the quantity and quality of Skywork-MathQA dataset across varying difficulty levels. Most importantly, we provide several practical takeaways to enhance math reasoning abilities in LLMs for both research and industry applications.
