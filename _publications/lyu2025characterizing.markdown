---
layout: publication
title: 'Characterizing Bias: Benchmarking Large Language Models In Simplified Versus Traditional Chinese'
authors: Hanjia Lyu, Jiebo Luo, Jian Kang, Allison Koenecke
conference: "Arxiv"
year: 2025
bibkey: lyu2025characterizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22645"}
  - {name: "Code", url: "https://github.com/brucelyu17/SC-TC-Bench)"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Tokenization', 'Ethics and Bias', 'Has Code', 'Prompting']
---
While the capabilities of Large Language Models (LLMs) have been studied in both Simplified and Traditional Chinese, it is yet unclear whether LLMs exhibit differential performance when prompted in these two variants of written Chinese. This understanding is critical, as disparities in the quality of LLM responses can perpetuate representational harms by ignoring the different cultural contexts underlying Simplified versus Traditional Chinese, and can exacerbate downstream harms in LLM-facilitated decision-making in domains such as education or hiring. To investigate potential LLM performance disparities, we design two benchmark tasks that reflect real-world scenarios: regional term choice (prompting the LLM to name a described item which is referred to differently in Mainland China and Taiwan), and regional name choice (prompting the LLM to choose who to hire from a list of names in both Simplified and Traditional Chinese). For both tasks, we audit the performance of 11 leading commercial LLM services and open-sourced models -- spanning those primarily trained on English, Simplified Chinese, or Traditional Chinese. Our analyses indicate that biases in LLM responses are dependent on both the task and prompting language: while most LLMs disproportionately favored Simplified Chinese responses in the regional term choice task, they surprisingly favored Traditional Chinese names in the regional name choice task. We find that these disparities may arise from differences in training data representation, written character preferences, and tokenization of Simplified and Traditional Chinese. These findings highlight the need for further analysis of LLM biases; as such, we provide an open-sourced benchmark dataset to foster reproducible evaluations of future LLM behavior across Chinese language variants (https://github.com/brucelyu17/SC-TC-Bench).
