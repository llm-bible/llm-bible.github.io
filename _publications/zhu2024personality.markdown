---
layout: publication
title: 'Personality Alignment Of Large Language Models'
authors: Minjun Zhu, Yixuan Weng, Linyi Yang, Yue Zhang
conference: "Arxiv"
year: 2024
bibkey: zhu2024personality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11779'}
  - {name: "Code", url: 'https://github.com/zhu-minjun/PAlign'}
tags: ['Reinforcement Learning', 'Has Code', 'Efficiency and Optimization', 'Tools']
---
Aligning large language models (LLMs) typically aim to reflect general human
values and behaviors, but they often fail to capture the unique characteristics
and preferences of individual users. To address this gap, we introduce the
concept of Personality Alignment. This approach tailors LLMs' responses and
decisions to match the specific preferences of individual users or closely
related groups. Inspired by psychometrics, we created the Personality Alignment
with Personality Inventories (PAPI) dataset, which includes data from over
320,000 real subjects across multiple personality assessments, including both
the Big Five Personality Factors and Dark Triad traits. This comprehensive
dataset enables quantitative evaluation of LLMs' alignment capabilities across
both positive and potentially problematic personality dimensions. Recognizing
the challenges of personality alignments, such as limited personal data,
diverse preferences, and scalability requirements, we developed an activation
intervention optimization method. This method enhances LLMs' ability to
efficiently align with individual behavioral preferences using minimal data and
computational resources. Remarkably, our method, PAS, achieves superior
performance while requiring only 1/5 of the optimization time compared to DPO,
offering practical value for personality alignment. Our work paves the way for
future AI systems to make decisions and reason in truly personality ways,
enhancing the relevance and meaning of AI interactions for each user and
advancing human-centered artificial intelligence. The dataset and code are
released at https://github.com/zhu-minjun/PAlign.
