---
layout: publication
title: 'LLM360 K2: Building A 65B 360-open-source Large Language Model From Scratch'
authors: Zhengzhong Liu, Bowen Tan, Hongyi Wang, Willie Neiswanger, Tianhua Tao, Haonan Li, Fajri Koto, Yuqi Wang, Suqi Sun, Omkar Pangarkar, Richard Fan, Yi Gu, Victor Miller, Liqun Ma, Liping Tang, Nikhil Ranjan, Yonghao Zhuang, Guowei He, Renxi Wang, Mingkai Deng, Robin Algayres, Yuanzhi Li, Zhiqiang Shen, Preslav Nakov, Eric Xing
conference: "Arxiv"
year: 2025
bibkey: liu2025building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07124"}
tags: ['Ethics and Bias', 'RAG', 'Training Techniques', 'Interpretability']
---
We detail the training of the LLM360 K2-65B model, scaling up our 360-degree
OPEN SOURCE approach to the largest and most powerful models under project
LLM360. While open-source LLMs continue to advance, the answer to "How are the
largest LLMs trained?" remains unclear within the community. The implementation
details for such high-capacity models are often protected due to business
considerations associated with their high cost. This lack of transparency
prevents LLM researchers from leveraging valuable insights from prior
experience, e.g., "What are the best practices for addressing loss spikes?" The
LLM360 K2 project addresses this gap by providing full transparency and access
to resources accumulated during the training of LLMs at the largest scale. This
report highlights key elements of the K2 project, including our first model, K2
DIAMOND, a 65 billion-parameter LLM that surpasses LLaMA-65B and rivals
LLaMA2-70B, while requiring fewer FLOPs and tokens. We detail the
implementation steps and present a longitudinal analysis of K2 DIAMOND's
capabilities throughout its training process. We also outline ongoing projects
such as TXT360, setting the stage for future models in the series. By offering
previously unavailable resources, the K2 project also resonates with the
360-degree OPEN SOURCE principles of transparency, reproducibility, and
accessibility, which we believe are vital in the era of resource-intensive AI
research.
