---
layout: publication
title: 'Golden Touchstone: A Comprehensive Bilingual Benchmark For Evaluating Financial Large Language Models'
authors: Xiaojun Wu, Junxi Liu, Huanyi Su, Zhouchi Lin, Yiyan Qi, Chengjin Xu, Jiajun Su, Jiajie Zhong, Fuwei Wang, Saizhuo Wang, Fengrui Hua, Jia Li, Jian Guo
conference: "Arxiv"
year: 2024
bibkey: wu2024golden
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06272"}
  - {name: "Code", url: "https://github.com/IDEA-FinAI/Golden-Touchstone},"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Has Code', 'Pre-Training']
---
As large language models become increasingly prevalent in the financial
sector, there is a pressing need for a standardized method to comprehensively
assess their performance. However, existing finance benchmarks often suffer
from limited language and task coverage, as well as challenges such as
low-quality datasets and inadequate adaptability for LLM evaluation. To address
these limitations, we propose "Golden Touchstone", the first comprehensive
bilingual benchmark for financial LLMs, which incorporates representative
datasets from both Chinese and English across eight core financial NLP tasks.
Developed from extensive open source data collection and industry-specific
demands, this benchmark includes a variety of financial tasks aimed at
thoroughly assessing models' language understanding and generation
capabilities. Through comparative analysis of major models on the benchmark,
such as GPT-4o Llama3, FinGPT and FinMA, we reveal their strengths and
limitations in processing complex financial information. Additionally, we
open-sourced Touchstone-GPT, a financial LLM trained through continual
pre-training and financial instruction tuning, which demonstrates strong
performance on the bilingual benchmark but still has limitations in specific
tasks.This research not only provides the financial large language models with
a practical evaluation tool but also guides the development and optimization of
future research. The source code for Golden Touchstone and model weight of
Touchstone-GPT have been made publicly available at
\url\{https://github.com/IDEA-FinAI/Golden-Touchstone\}, contributing to the
ongoing evolution of FinLLMs and fostering further research in this critical
area.
