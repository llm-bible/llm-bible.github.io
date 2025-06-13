---
layout: publication
title: 'Stepwise Perplexity-guided Refinement For Efficient Chain-of-thought Reasoning In Large Language Models'
authors: Yingqian Cui, Pengfei He, Jingying Zeng, Hui Liu, Xianfeng Tang, Zhenwei Dai, Yan Han, Chen Luo, Jing Huang, Zhen Li, Suhang Wang, Yue Xing, Jiliang Tang, Qi He
conference: "Arxiv"
year: 2025
bibkey: cui2025stepwise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13260"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Few-Shot']
---
Chain-of-Thought (CoT) reasoning, which breaks down complex tasks into
intermediate reasoning steps, has significantly enhanced the performance of
large language models (LLMs) on challenging tasks. However, the detailed
reasoning process in CoT often incurs long generation times and high
computational costs, partly due to the inclusion of unnecessary steps. To
address this, we propose a method to identify critical reasoning steps using
perplexity as a measure of their importance: a step is deemed critical if its
removal causes a significant increase in perplexity. Our method enables models
to focus solely on generating these critical steps. This can be achieved
through two approaches: refining demonstration examples in few-shot CoT or
fine-tuning the model using selected examples that include only critical steps.
Comprehensive experiments validate the effectiveness of our method, which
achieves a better balance between the reasoning accuracy and efficiency of CoT.
