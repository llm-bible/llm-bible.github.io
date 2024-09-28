---
layout: publication
title: Generative Explore-Exploit Training-free Optimization of Generative Recommender Systems using LLM Optimizers
authors: Senel Lütfi Kerem, Fetahu Besnik, Yoshida Davis, Chen Zhiyu, Castellucci Giuseppe, Vedula Nikhita, Choi Jason, Malmasi Shervin
conference: "Arxiv"
year: 2024
bibkey: senel2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05255"}
tags: ['ARXIV', 'Efficiency And Optimization', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Recommender systems are widely used to suggest engaging content and Large Language Models (LLMs) have given rise to generative recommenders. Such systems can directly generate items including for open-set tasks like question suggestion. While the world knowledge of LLMs enable good recommendations improving the generated content through user feedback is challenging as continuously fine-tuning LLMs is prohibitively expensive. We present a training-free approach for optimizing generative recommenders by connecting user feedback loops to LLM-based optimizers. We propose a generative explore-exploit method that can not only exploit generated items with known high engagement but also actively explore and discover hidden population preferences to improve recommendation quality. We evaluate our approach on question generation in two domains (e-commerce and general knowledge) and model user feedback with Click Through Rate (CTR). Experiments show our LLM-based explore-exploit approach can iteratively improve recommendations and consistently increase CTR. Ablation analysis shows that generative exploration is key to learning user preferences avoiding the pitfalls of greedy exploit-only approaches. A human evaluation strongly supports our quantitative findings.
