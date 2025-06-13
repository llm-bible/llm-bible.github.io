---
layout: publication
title: 'Lexpro-1.0 Technical Report'
authors: Haotian Chen, Yanyu Xu, Boyan Wang, Chaoyue Zhao, Xiaoyu Han, Fang Wang, Lizhen Cui, Yonghui Xu
conference: "Arxiv"
year: 2025
bibkey: chen2025lexpro
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06949"}
tags: ['Fine-Tuning', 'Agentic', 'Applications', 'Interpretability and Explainability', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
In this report, we introduce our first-generation reasoning model,
LexPro-1.0, a large language model designed for the highly specialized Chinese
legal domain, offering comprehensive capabilities to meet diverse realistic
needs. Existing legal LLMs face two primary challenges. Firstly, their design
and evaluation are predominantly driven by computer science perspectives,
leading to insufficient incorporation of legal expertise and logic, which is
crucial for high-precision legal applications, such as handling complex
prosecutorial tasks. Secondly, these models often underperform due to a lack of
comprehensive training data from the legal domain, limiting their ability to
effectively address real-world legal scenarios. To address this, we first
compile millions of legal documents covering over 20 types of crimes from 31
provinces in China for model training. From the extensive dataset, we further
select high-quality for supervised fine-tuning, ensuring enhanced relevance and
precision. The model further undergoes large-scale reinforcement learning
without additional supervision, emphasizing the enhancement of its reasoning
capabilities and explainability. To validate its effectiveness in complex legal
applications, we also conduct human evaluations with legal experts. We develop
fine-tuned models based on DeepSeek-R1-Distilled versions, available in three
dense configurations: 14B, 32B, and 70B.
