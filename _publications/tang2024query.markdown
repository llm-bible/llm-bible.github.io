---
layout: publication
title: 'Quest: Query-aware Sparsity For Efficient Long-context LLM Inference'
authors: Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han
conference: "Arxiv"
year: 2024
bibkey: tang2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10774"}
  - {name: "Code", url: "http://github.com/mit-han-lab/Quest"}
tags: ['Has Code', 'Model Architecture', 'Transformer', 'Attention Mechanism']
---
As the demand for long-context large language models (LLMs) increases, models
with context windows of up to 128K or 1M tokens are becoming increasingly
prevalent. However, long-context LLM inference is challenging since the
inference speed decreases significantly as the sequence length grows. This
slowdown is primarily caused by loading a large KV cache during self-attention.
Previous works have shown that a small portion of critical tokens will dominate
the attention outcomes. However, we observe the criticality of a token highly
depends on the query. To this end, we propose Quest, a query-aware KV cache
selection algorithm. Quest keeps track of the minimal and maximal Key values in
KV cache pages and estimates the criticality of a given page using Query
vectors. By only loading the Top-K critical KV cache pages for attention, Quest
significantly speeds up self-attention without sacrificing accuracy. We show
that Quest can achieve up to 2.23x self-attention speedup, which reduces
inference latency by 7.03x while performing well on tasks with long
dependencies with negligible accuracy loss. Code is available at
http://github.com/mit-han-lab/Quest .
