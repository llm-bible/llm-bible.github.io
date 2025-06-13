---
layout: publication
title: 'When Reasoning Meets Compression: Benchmarking Compressed Large Reasoning Models On Complex Reasoning Tasks'
authors: Nan Zhang, Yusen Zhang, Prasenjit Mitra, Rui Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02010"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Language Modeling', 'Distillation', 'GPT', 'Pruning', 'Quantization']
---
Recent open-source large reasoning models (LRMs) exhibit strong performance
on complex reasoning tasks, but their large parameter count makes them
prohibitively expensive for individuals. The compression of large language
models (LLMs) offers an effective solution to reduce cost of computational
resources. However, systematic studies on the performance of compressed LLMs in
complex reasoning tasks, especially for LRMs, are lacking. Most works on
quantization and pruning focus on preserving language modeling performance,
while existing distillation works do not comprehensively benchmark student
models based on reasoning difficulty or compression impact on knowledge and
reasoning. In this paper, we benchmark compressed DeepSeek-R1 models on four
different reasoning datasets (AIME 2024, FOLIO, Temporal Sequences of BIG-Bench
Hard, and MuSiQue), ranging from mathematical to multihop reasoning, using
quantization, distillation, and pruning methods. We benchmark 2.51-, 1.73-, and
1.58-bit R1 models that adopt dynamic quantization. We also benchmark distilled
R1 models that are based on LLaMA or Qwen and run SparseGPT on them to obtain
various sparsity levels. Studying the performance and behavior of compressed
LRMs, we report their performance scores and test-time compute (number of
tokens spent on each question). Notably, using MuSiQue, we find that parameter
count has a much greater impact on LRMs' knowledge memorization than on their
reasoning capability, which can inform the choice of compression techniques.
Through our empirical analysis of test-time compute, we find that shorter model
outputs generally achieve better performance than longer ones across several
benchmarks for both R1 and its compressed variants, highlighting the need for
more concise reasoning chains.
