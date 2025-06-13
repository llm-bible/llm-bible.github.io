---
layout: publication
title: 'Towards Thinking-optimal Scaling Of Test-time Compute For LLM Reasoning'
authors: Wenkai Yang, Shuming Ma, Yankai Lin, Furu Wei
conference: "Arxiv"
year: 2025
bibkey: yang2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18080"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Distillation']
---
Recent studies have shown that making a model spend more time thinking
through longer Chain of Thoughts (CoTs) enables it to gain significant
improvements in complex reasoning tasks. While current researches continue to
explore the benefits of increasing test-time compute by extending the CoT
lengths of Large Language Models (LLMs), we are concerned about a potential
issue hidden behind the current pursuit of test-time scaling: Would excessively
scaling the CoT length actually bring adverse effects to a model's reasoning
performance? Our explorations on mathematical reasoning tasks reveal an
unexpected finding that scaling with longer CoTs can indeed impair the
reasoning performance of LLMs in certain domains. Moreover, we discover that
there exists an optimal scaled length distribution that differs across
different domains. Based on these insights, we propose a Thinking-Optimal
Scaling strategy. Our method first uses a small set of seed data with varying
response length distributions to teach the model to adopt different reasoning
efforts for deep thinking. Then, the model selects its shortest correct
response under different reasoning efforts on additional problems for
self-improvement. Our self-improved models built upon Qwen2.5-32B-Instruct
outperform other distillation-based 32B o1-like models across various math
benchmarks, and achieve performance on par with QwQ-32B-Preview.
