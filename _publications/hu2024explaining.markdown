---
layout: publication
title: 'Explaining Length Bias In Llm-based Preference Evaluations'
authors: Zhengyu Hu, Linxin Song, Jieyu Zhang, Zheyuan Xiao, Tianfu Wang, Zhengyu Chen, Nicholas Jing Yuan, Jianxun Lian, Kaize Ding, Hui Xiong
conference: "Arxiv"
year: 2024
bibkey: hu2024explaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01085"}
tags: ['Ethics and Bias', 'Reinforcement Learning']
---
The use of large language models (LLMs) as judges, particularly in preference
comparisons, has become widespread, but this reveals a notable bias towards
longer responses, undermining the reliability of such evaluations. To better
understand such bias, we propose to decompose the preference evaluation metric,
specifically the win rate, into two key components: desirability and
information mass, where the former is length-independent and related to
trustworthiness such as correctness, toxicity, and consistency, and the latter
is length-dependent and represents the amount of information in the response.
We empirically demonstrated the decomposition through controlled experiments
and found that response length impacts evaluations by influencing information
mass. To derive a reliable evaluation metric that assesses content quality
without being confounded by response length, we propose AdapAlpaca, a simple
yet effective adjustment to win rate measurement. Specifically, AdapAlpaca
ensures a fair comparison of response quality by aligning the lengths of
reference and test model responses under equivalent length intervals.
