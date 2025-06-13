---
layout: publication
title: 'Token-level Proximal Policy Optimization For Query Generation'
authors: Yichen Ouyang, Lu Wang, Fangkai Yang, Pu Zhao, Chenghua Huang, Jianfeng Liu, Bochen Pang, Yaming Yang, Yuefeng Zhan, Hao Sun, Qingwei Lin, Saravan Rajmohan, Weiwei Deng, Dongmei Zhang, Feng Sun, Qi Zhang
conference: "Arxiv"
year: 2024
bibkey: ouyang2024token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00722'}
tags: ['Agentic', 'Language Modeling', 'RAG', 'Security', 'Efficiency and Optimization', 'Tools', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Query generation is a critical task for web search engines (e.g. Google,
Bing) and recommendation systems. Recently, state-of-the-art query generation
methods leverage Large Language Models (LLMs) for their strong capabilities in
context understanding and text generation. However, they still face challenges
in generating high-quality queries in terms of inferring user intent based on
their web search interaction history. In this paper, we propose Token-level
Proximal Policy Optimization (TPPO), a noval approach designed to empower LLMs
perform better in query generation through fine-tuning. TPPO is based on the
Reinforcement Learning from AI Feedback (RLAIF) paradigm, consisting of a
token-level reward model and a token-level proximal policy optimization module
to address the sparse reward challenge in traditional RLAIF frameworks. To
evaluate the effectiveness and robustness of TPPO, we conducted experiments on
both open-source dataset and an industrial dataset that was collected from a
globally-used search engine. The experimental results demonstrate that TPPO
significantly improves the performance of query generation for LLMs and
outperforms its existing competitors.
