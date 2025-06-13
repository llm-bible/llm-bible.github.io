---
layout: publication
title: 'Chart-hqa: A Benchmark For Hypothetical Question Answering In Charts'
authors: Xiangnan Chen, Yuancheng Fang, Qian Xiao, Juncheng Li, Jun Lin, Siliang Tang, Yi Yang, Yueting Zhuang
conference: "Arxiv"
year: 2025
bibkey: chen2025chart
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04095'}
tags: ['Attention Mechanism', 'Dataset', 'RAG', 'Model Architecture', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Multimodal Large Language Models (MLLMs) have garnered significant attention
for their strong visual-semantic understanding. Most existing chart benchmarks
evaluate MLLMs' ability to parse information from charts to answer questions.
However, they overlook the inherent output biases of MLLMs, where models rely
on their parametric memory to answer questions rather than genuinely
understanding the chart content. To address this limitation, we introduce a
novel Chart Hypothetical Question Answering (HQA) task, which imposes
assumptions on the same question to compel models to engage in counterfactual
reasoning based on the chart content. Furthermore, we introduce HAI, a human-AI
interactive data synthesis approach that leverages the efficient text-editing
capabilities of LLMs alongside human expert knowledge to generate diverse and
high-quality HQA data at a low cost. Using HAI, we construct Chart-HQA, a
challenging benchmark synthesized from publicly available data sources.
Evaluation results on 18 MLLMs of varying model sizes reveal that current
models face significant generalization challenges and exhibit imbalanced
reasoning performance on the HQA task.
