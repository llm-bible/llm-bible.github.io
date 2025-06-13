---
layout: publication
title: 'Improving Data Efficiency Via Curating Llm-driven Rating Systems'
authors: Jinlong Pang, Jiaheng Wei, Ankit Parag Shah, Zhaowei Zhu, Yaxuan Wang, Chen Qian, Yang Liu, Yujia Bao, Wei Wei
conference: "Arxiv"
year: 2024
bibkey: pang2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10877"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Scaling Laws', 'GPT', 'Ethics and Bias', 'Large-Scale Training', 'Pre-Training']
---
Instruction tuning is critical for adapting large language models (LLMs) to
downstream tasks, and recent studies have demonstrated that small amounts of
human-curated data can outperform larger datasets, challenging traditional data
scaling laws. While LLM-based data quality rating systems offer a
cost-effective alternative to human annotation, they often suffer from
inaccuracies and biases, even in powerful models like GPT-4. In this work, we
introduce DS2, a Diversity-aware Score curation method for Data Selection. By
systematically modeling error patterns through a score transition matrix, DS2
corrects LLM-based scores and promotes diversity in the selected data samples.
Our approach shows that a curated subset (just 3.3% of the original dataset)
outperforms full-scale datasets (300k samples) across various machine-alignment
benchmarks, and matches or surpasses human-aligned datasets such as LIMA with
the same sample size (1k samples). These findings challenge conventional data
scaling assumptions, highlighting that redundant, low-quality samples can
degrade performance and reaffirming that "more can be less."
