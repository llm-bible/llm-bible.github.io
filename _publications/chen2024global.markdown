---
layout: publication
title: 'GUIDE: A Global Unified Inference Engine For Deploying Large Language Models In Heterogeneous Environments'
authors: Yanyu Chen, Ganhong Huang
conference: "Arxiv"
year: 2024
bibkey: chen2024global
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04788'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Efficiently deploying large language models (LLMs) in real-world scenarios
remains a critical challenge, primarily due to hardware heterogeneity,
inference framework limitations, and workload complexities.Efficiently
deploying large language models (LLMs) in real-world scenarios remains a
critical challenge, primarily due to hardware heterogeneity, inference
framework limitations, and workload complexities. These challenges often lead
to inefficiencies in memory utilization, latency, and throughput, hindering the
effective deployment of LLMs, especially for non-experts. Through extensive
experiments, we identify key performance bottlenecks, including sudden drops in
memory utilization, latency fluctuations with varying batch sizes, and
inefficiencies in multi-GPU configurations. These insights reveal a vast
optimization space shaped by the intricate interplay of hardware, frameworks,
and workload parameters. This underscores the need for a systematic approach to
optimize LLM inference, motivating the design of our framework, GUIDE. GUIDE
leverages dynamic modeling and simulation-based optimization to address these
issues, achieving prediction errors between 9.9% and 42.3% for key metrics such
as batch latency, TTFT, and decode throughput. By effectively bridging the gap
between theoretical performance and practical deployment, our framework
empowers practitioners, particularly non-specialists, to make data-driven
decisions and unlock the full potential of LLMs in heterogeneous environments
cheaply.
