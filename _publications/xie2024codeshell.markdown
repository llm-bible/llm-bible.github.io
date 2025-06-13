---
layout: publication
title: 'Codeshell Technical Report'
authors: Rui Xie, Zhengran Zeng, Zhuohao Yu, Chang Gao, Shikun Zhang, Wei Ye
conference: "Arxiv"
year: 2024
bibkey: xie2024codeshell
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15747"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Pre-Training', 'Attention Mechanism']
---
Code large language models mark a pivotal breakthrough in artificial
intelligence. They are specifically crafted to understand and generate
programming languages, significantly boosting the efficiency of coding
development workflows. In this technical report, we present CodeShell-Base, a
seven billion-parameter foundation model with 8K context length, showcasing
exceptional proficiency in code comprehension. By incorporating Grouped-Query
Attention and Rotary Positional Embedding into GPT-2, CodeShell-Base integrates
the structural merits of StarCoder and CodeLlama and forms its unique
architectural design. We then carefully built a comprehensive data
pre-processing process, including similar data deduplication, perplexity-based
data filtering, and model-based data filtering. Through this process, We have
curated 100 billion high-quality pre-training data from GitHub. Benefiting from
the high-quality data, CodeShell-Base outperforms CodeLlama in Humaneval after
training on just 500 billion tokens (5 epochs). We have conducted extensive
experiments across multiple language datasets, including Python, Java, and C++,
and the results indicate that our model possesses robust foundational
capabilities in code comprehension and generation.
