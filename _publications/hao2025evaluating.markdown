---
layout: publication
title: 'Evaluating Personalized Tool-augmented Llms From The Perspectives Of Personalization And Proactivity'
authors: Yupu Hao, Pengfei Cao, Zhuoran Jin, Huanxuan Liao, Yubo Chen, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2025
bibkey: hao2025evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00771'}
  - {name: "Code", url: 'https://github.com/hypasd-art/ETAPP'}
tags: ['Agentic', 'Has Code', 'Language Modeling', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Ethics and Bias', 'Pretraining Methods']
---
Personalized tool utilization is essential for aligning large language models
(LLMs) with user preference in interaction scenarios with various tools.
However, most of the current benchmarks primarily focus on either
personalization of text generation or direct tool-utilizing, without
considering both. In this work, we introduce a novel benchmark ETAPP for
evaluating personalized tool invocation, establishing a sandbox environment,
and a comprehensive dataset of 800 testing cases covering diverse user
profiles. To improve the accuracy of our evaluation, we propose a
key-point-based LLM evaluation method, mitigating biases in the LLM-as-a-judge
system by manually annotating key points for each test case and providing them
to LLM as the reference. Additionally, we evaluate the excellent LLMs and
provide an in-depth analysis. Furthermore, we investigate the impact of
different tool-invoking strategies on LLMs' personalization performance and the
effects of fine-tuning in our task. The effectiveness of our preference-setting
and key-point-based evaluation method is also validated. Our findings offer
insights into improving personalized LLM agents. Our Code is available at
https://github.com/hypasd-art/ETAPP.
