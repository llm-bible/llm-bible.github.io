---
layout: publication
title: 'Aligning Codellms With Direct Preference Optimization'
authors: Yibo Miao, Bofei Gao, Shanghaoran Quan, Junyang Lin, Daoguang Zan, Jiaheng Liu, Jian Yang, Tianyu Liu, Zhijie Deng
conference: "Arxiv"
year: 2024
bibkey: miao2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18585"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
The last year has witnessed the rapid progress of large language models
(LLMs) across diverse domains. Among them, CodeLLMs have garnered particular
attention because they can not only assist in completing various programming
tasks but also represent the decision-making and logical reasoning capabilities
of LLMs. However, current CodeLLMs mainly focus on pre-training and supervised
fine-tuning scenarios, leaving the alignment stage, which is important for
post-training LLMs, under-explored. This work first identifies that the
commonly used PPO algorithm may be suboptimal for the alignment of CodeLLM
because the involved reward rules are routinely coarse-grained and potentially
flawed. We then advocate addressing this using the DPO algorithm. Based on only
preference data pairs, DPO can render the model rank data automatically, giving
rise to a fine-grained rewarding pattern more robust than human intervention.
We also contribute a pipeline for collecting preference pairs for DPO on
CodeLLMs. Studies show that our method significantly improves the performance
of existing CodeLLMs on benchmarks such as MBPP and HumanEval.
