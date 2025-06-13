---
layout: publication
title: 'Generative Explore-exploit: Training-free Optimization Of Generative Recommender Systems Using LLM Optimizers'
authors: Lütfi Kerem Senel, Besnik Fetahu, Davis Yoshida, Zhiyu Chen, Giuseppe Castellucci, Nikhita Vedula, Jason Choi, Shervin Malmasi
conference: "Arxiv"
year: 2024
bibkey: senel2024generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.05255'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'RecSys', 'Reinforcement Learning', 'Pretraining Methods']
---
Recommender systems are widely used to suggest engaging content, and Large
Language Models (LLMs) have given rise to generative recommenders. Such systems
can directly generate items, including for open-set tasks like question
suggestion. While the world knowledge of LLMs enable good recommendations,
improving the generated content through user feedback is challenging as
continuously fine-tuning LLMs is prohibitively expensive. We present a
training-free approach for optimizing generative recommenders by connecting
user feedback loops to LLM-based optimizers. We propose a generative
explore-exploit method that can not only exploit generated items with known
high engagement, but also actively explore and discover hidden population
preferences to improve recommendation quality. We evaluate our approach on
question generation in two domains (e-commerce and general knowledge), and
model user feedback with Click Through Rate (CTR). Experiments show our
LLM-based explore-exploit approach can iteratively improve recommendations, and
consistently increase CTR. Ablation analysis shows that generative exploration
is key to learning user preferences, avoiding the pitfalls of greedy
exploit-only approaches. A human evaluation strongly supports our quantitative
findings.
