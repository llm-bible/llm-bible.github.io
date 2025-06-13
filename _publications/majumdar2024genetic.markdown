---
layout: publication
title: 'Genetic Instruct: Scaling Up Synthetic Generation Of Coding Instructions For Large Language Models'
authors: Somshubra Majumdar, Vahid Noroozi, Mehrzad Samadi, Sean Narenthiran, Aleksander Ficek, Wasi Uddin Ahmad, Jocelyn Huang, Jagadeesh Balam, Boris Ginsburg
conference: "Arxiv"
year: 2024
bibkey: majumdar2024genetic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.21077'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) require high quality instruction data for effective alignment, particularly in code generation tasks where expert curated datasets are expensive to produce. We present Genetic-Instruct, a scalable algorithm for synthesizing large-scale, high quality coding instructions using evolutionary principles. Starting from a small set of seed instructions, Genetic-Instruct generates diverse and challenging instruction-code pairs by leveraging an Instructor-LLM for generation, a Coder-LLM for code synthesis, and a Judge-LLM for automatic quality evaluation. Our proposed approach is highly parallelizable and effective even with a small seed data and weaker generator models. We generated more than 7.5 million coding instructions with the proposed approach. Then we evaluated it by fine-tuning LLMs with the synthetic samples and demonstrated a significant improvement in their code generation capability compared to the other synthetic generation approaches and publicly available datasets. Our results highlight the efficiency, scalability, and generalizability of the Genetic-Instruct framework.
