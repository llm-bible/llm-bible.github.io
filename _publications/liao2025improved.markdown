---
layout: publication
title: 'Improved Visual-spatial Reasoning Via R1-zero-like Training'
authors: Zhenyi Liao, Qingsong Xie, Yanhao Zhang, Zijian Kong, Haonan Lu, Zhenyu Yang, Zhijie Deng
conference: "Arxiv"
year: 2025
bibkey: liao2025improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00883"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
Increasing attention has been placed on improving the reasoning capacities of
multi-modal large language models (MLLMs). As the cornerstone for AI agents
that function in the physical realm, video-based visual-spatial intelligence
(VSI) emerges as one of the most pivotal reasoning capabilities of MLLMs. This
work conducts a first, in-depth study on improving the visual-spatial reasoning
of MLLMs via R1-Zero-like training. Technically, we first identify that the
visual-spatial reasoning capacities of small- to medium-sized Qwen2-VL models
cannot be activated via Chain of Thought (CoT) prompts. We then incorporate
GRPO training for improved visual-spatial reasoning, using the carefully
curated VSI-100k dataset, following DeepSeek-R1-Zero. During the investigation,
we identify the necessity to keep the KL penalty (even with a small value) in
GRPO. With just 120 GPU hours, our vsGRPO-2B model, fine-tuned from
Qwen2-VL-2B, can outperform the base model by 12.1% and surpass GPT-4o.
Moreover, our vsGRPO-7B model, fine-tuned from Qwen2-VL-7B, achieves
performance comparable to that of the best open-source model
LLaVA-NeXT-Video-72B. Additionally, we compare vsGRPO to supervised fine-tuning
and direct preference optimization baselines and observe strong performance
superiority. The code and dataset will be available soon.
