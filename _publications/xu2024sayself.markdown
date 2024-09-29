---
layout: publication
title: Sayself Teaching Llms To Express Confidence With Self-reflective Rationales
authors: Xu Tianyang, Wu Shujin, Diao Shizhe, Liu Xiaoze, Wang Xingyao, Chen Yangyi, Gao Jing
conference: "Arxiv"
year: 2024
bibkey: xu2024sayself
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20974"}
  - {name: "Code", url: "https://github.com/xu1868/SaySelf"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) often generate inaccurate or fabricated information and generally fail to indicate their confidence which limits their broader applications. Previous work elicits confidence from LLMs by direct or self-consistency prompting or constructing specific datasets for supervised finetuning. The prompting-based approaches have inferior performance and the training-based approaches are limited to binary or inaccurate group-level confidence estimates. In this work we present the advanced SaySelf a training framework that teaches LLMs to express more accurate fine-grained confidence estimates. In addition beyond the confidence scores SaySelf initiates the process of directing LLMs to produce self-reflective rationales that clearly identify gaps in their parametric knowledge and explain their uncertainty. This is achieved by using an LLM to automatically summarize the uncertainties in specific knowledge via natural language. The summarization is based on the analysis of the inconsistency in multiple sampled reasoning chains and the resulting data is utilized for supervised fine-tuning. Moreover we utilize reinforcement learning with a meticulously crafted reward function to calibrate the confidence estimates motivating LLMs to deliver accurate high-confidence predictions and to penalize overconfidence in erroneous outputs. Experimental results in both in-distribution and out-of-distribution datasets demonstrate the effectiveness of SaySelf in reducing the confidence calibration error and maintaining the task performance. We show that the generated self-reflective rationales are reasonable and can further contribute to the calibration. The code is made public at https://github.com/xu1868/SaySelf.
