---
layout: publication
title: 'Vision-r1: Incentivizing Reasoning Capability In Multimodal Large Language Models'
authors: Wenxuan Huang, Bohan Jia, Zijie Zhai, Shaosheng Cao, Zheyu Ye, Fei Zhao, Zhe Xu, Yao Hu, Shaohui Lin
conference: "Arxiv"
year: 2025
bibkey: huang2025vision
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06749'}
  - {name: "Code", url: 'https://github.com/Osilly/Vision-R1'}
tags: ['Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
DeepSeek-R1-Zero has successfully demonstrated the emergence of reasoning
capabilities in LLMs purely through Reinforcement Learning (RL). Inspired by
this breakthrough, we explore how RL can be utilized to enhance the reasoning
capability of MLLMs. However, direct training with RL struggles to activate
complex reasoning capabilities such as questioning and reflection in MLLMs, due
to the absence of substantial high-quality multimodal reasoning data. To
address this issue, we propose the reasoning MLLM, Vision-R1, to improve
multimodal reasoning capability. Specifically, we first construct a
high-quality multimodal CoT dataset without human annotations by leveraging an
existing MLLM and DeepSeek-R1 through modality bridging and data filtering to
obtain a 200K multimodal CoT dataset, Vision-R1-cold dataset. It serves as
cold-start initialization data for Vision-R1. To mitigate the optimization
challenges caused by overthinking after cold start, we propose Progressive
Thinking Suppression Training (PTST) strategy and employ Group Relative Policy
Optimization (GRPO) with the hard formatting result reward function to
gradually refine the model's ability to learn correct and complex reasoning
processes on a 10K multimodal math dataset. Comprehensive experiments show our
model achieves an average improvement of \\(\sim\\)6% across various multimodal
math reasoning benchmarks. Vision-R1-7B achieves a 73.5% accuracy on the widely
used MathVista benchmark, which is only 0.4% lower than the leading reasoning
model, OpenAI O1. The datasets and code will be released in:
https://github.com/Osilly/Vision-R1 .
