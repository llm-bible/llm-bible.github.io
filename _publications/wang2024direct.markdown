---
layout: publication
title: 'Direct Judgement Preference Optimization'
authors: Peifeng Wang, Austin Xu, Yilun Zhou, Caiming Xiong, Shafiq Joty
conference: "Arxiv"
year: 2024
bibkey: wang2024direct
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14664'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Applications', 'GPT', 'Survey Paper', 'Ethics and Bias']
---
Auto-evaluation is crucial for assessing response quality and offering
feedback for model development. Recent studies have explored training large
language models (LLMs) as generative judges to evaluate and critique other
models' outputs. In this work, we investigate the idea of learning from both
positive and negative data with preference optimization to enhance the
evaluation capabilities of LLM judges across an array of different use cases.
We achieve this by employing three approaches to collect the preference pairs
for different use cases, each aimed at improving our generative judge from a
different perspective. Our comprehensive study over a wide range of benchmarks
demonstrates the effectiveness of our method. In particular, our generative
judge achieves the best performance on 10 out of 13 benchmarks, outperforming
strong baselines like GPT-4o and specialized judge models. Further analysis
show that our judge model robustly counters inherent biases such as position
and length bias, flexibly adapts to any evaluation protocol specified by
practitioners, and provides helpful language feedback for improving downstream
generator models.
