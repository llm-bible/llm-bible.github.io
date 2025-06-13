---
layout: publication
title: 'EFPC: Towards Efficient And Flexible Prompt Compression'
authors: Yun-hao Cao, Yangsong Wang, Shuzheng Hao, Zhenxing Li, Chengjun Zhan, Sichao Liu, Yi-qi Hu
conference: "Arxiv"
year: 2025
bibkey: cao2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07956"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
The emergence of large language models (LLMs) like GPT-4 has revolutionized
natural language processing (NLP), enabling diverse, complex tasks. However,
extensive token counts lead to high computational and financial burdens. To
address this, we propose Efficient and Flexible Prompt Compression (EFPC), a
novel method unifying task-aware and task-agnostic compression for a favorable
accuracy-efficiency trade-off. EFPC uses GPT-4 to generate compressed prompts
and integrates them with original prompts for training. During training and
inference, we selectively prepend user instructions and compress prompts based
on predicted probabilities. EFPC is highly data-efficient, achieving
significant performance with minimal data. Compared to the state-of-the-art
method LLMLingua-2, EFPC achieves a 4.8% relative improvement in F1-score with
1% additional data at a 4x compression rate, and an 11.4% gain with 10%
additional data on the LongBench single-doc QA benchmark. EFPC's unified
framework supports broad applicability and enhances performance across various
models, tasks, and domains, offering a practical advancement in NLP.
