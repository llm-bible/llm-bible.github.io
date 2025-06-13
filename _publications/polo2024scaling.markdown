---
layout: publication
title: 'Sloth: Scaling Laws For LLM Skills To Predict Multi-benchmark Performance Across Families'
authors: Felipe Maia Polo, Seamus Somerstep, Leshem Choshen, Yuekai Sun, Mikhail Yurochkin
conference: "Arxiv"
year: 2024
bibkey: polo2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06540"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'RAG', 'Large-Scale Training', 'Pre-Training']
---
Scaling laws for large language models (LLMs) predict model performance based
on parameters like size and training data. However, differences in training
configurations and data processing across model families lead to significant
variations in benchmark performance, making it difficult for a single scaling
law to generalize across all LLMs. On the other hand, training family-specific
scaling laws requires training models of varying sizes for every family. In
this work, we propose Skills Scaling Laws (SSLaws, pronounced as Sloth), a
novel scaling law that leverages publicly available benchmark data and assumes
LLM performance is driven by low-dimensional latent skills, such as reasoning
and instruction following. These latent skills are influenced by computational
resources like model size and training tokens but with varying efficiencies
across model families. Sloth exploits correlations across benchmarks to provide
more accurate and interpretable predictions while alleviating the need to train
multiple LLMs per family. We present both theoretical results on parameter
identification and empirical evaluations on 12 prominent benchmarks, from Open
LLM Leaderboard v1/v2, demonstrating that Sloth predicts LLM performance
efficiently and offers insights into scaling behaviors for complex downstream
tasks and increased test-time compute.
