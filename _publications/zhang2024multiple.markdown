---
layout: publication
title: 'Multiple-choice Questions Are Efficient And Robust LLM Evaluators'
authors: Ziyin Zhang, Zhaokun Jiang, Lizhen Xu, Hongkun Hao, Rui Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024multiple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.11966'}
  - {name: "Code", url: 'https://github.com/Geralt-Targaryen/MC-Evaluation'}
tags: ['Has Code', 'Uncategorized']
---
We present GSM-MC, a multiple-choice (MC) dataset constructed by collecting
answers and incorrect predictions on GSM8K from 60 open-source models. Through
extensive experiments, we show that LLMs' performance on the MC version of this
popular benchmark is strongly correlated with their performance on the original
version and is quite robust to distractor choices and option orders, while the
evaluation time is reduced by a factor of up to 30. Following similar
procedures, we introduce MATH-MC, constructed from MATH, and PythonIO, a new
program reasoning MC dataset constructed from HumanEval and MBPP. Experimental
results indicate that LLMs' performance on these MC benchmarks leaves much room
for improvement. Our data and code are available at
https://github.com/Geralt-Targaryen/MC-Evaluation.
