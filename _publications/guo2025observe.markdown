---
layout: publication
title: 'Observe-r1: Unlocking Reasoning Abilities Of Mllms With Dynamic Progressive Reinforcement Learning'
authors: Zirun Guo, Minjie Hong, Tao Jin
conference: "Arxiv"
year: 2025
bibkey: guo2025observe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12432"}
  - {name: "Code", url: "https://github.com/zrguo/Observe-R1"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code']
---
Reinforcement Learning (RL) has shown promise in improving the reasoning abilities of Large Language Models (LLMs). However, the specific challenges of adapting RL to multimodal data and formats remain relatively unexplored. In this work, we present Observe-R1, a novel framework aimed at enhancing the reasoning capabilities of multimodal large language models (MLLMs). We draw inspirations from human learning progression--from simple to complex and easy to difficult, and propose a gradual learning paradigm for MLLMs. To this end, we construct the NeuraLadder dataset, which is organized and sampled according to the difficulty and complexity of data samples for RL training. To tackle multimodal tasks, we introduce a multimodal format constraint that encourages careful observation of images, resulting in enhanced visual abilities and clearer and more structured responses. Additionally, we implement a bonus reward system that favors concise, correct answers within a length constraint, alongside a dynamic weighting mechanism that prioritizes uncertain and medium-difficulty problems, ensuring that more informative samples have a greater impact on training. Our experiments with the Qwen2.5-VL-3B and Qwen2.5-VL-7B models on 20k samples from the NeuraLadder dataset show that Observe-R1 outperforms a series of larger reasoning models on both reasoning and general benchmarks, achieving superior clarity and conciseness in reasoning chains. Ablation studies validate the effectiveness of our strategies, highlighting the robustness and generalization of our approach. The dataset and code will be released at https://github.com/zrguo/Observe-R1.
