---
layout: publication
title: 'Exploring Self-supervised Logic-enhanced Training For Large Language Models'
authors: Fangkai Jiao, Zhiyang Teng, Bosheng Ding, Zhengyuan Liu, Nancy F. Chen, Shafiq Joty
conference: "Arxiv"
year: 2023
bibkey: jiao2023exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.13718'}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Existing efforts to improve logical reasoning ability of language models have
predominantly relied on supervised fine-tuning, hindering generalization to new
domains and/or tasks. The development of Large Langauge Models (LLMs) has
demonstrated the capacity of compressing abundant knowledge into a single
proxy, enabling them to tackle multiple tasks effectively. Our preliminary
experiments, nevertheless, show that LLMs do not show capability on logical
reasoning. The performance of LLMs on logical reasoning benchmarks is far
behind the existing state-of-the-art baselines. In this paper, we make the
first attempt to investigate the feasibility of incorporating logical knowledge
through self-supervised post-training, and activating it via in-context
learning, which we termed as LogicLLM. Specifically, we devise an
auto-regressive objective variant of MERIt and integrate it with two LLM
series, i.e., FLAN-T5 and LLaMA, with parameter size ranging from 3 billion to
13 billion. The results on two challenging logical reasoning benchmarks
demonstrate the effectiveness of LogicLLM. Besides, we conduct extensive
ablation studies to analyze the key factors in designing logic-oriented proxy
tasks.
