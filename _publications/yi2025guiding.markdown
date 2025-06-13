---
layout: publication
title: 'Shorterbetter: Guiding Reasoning Models To Find Optimal Inference Length For Efficient Reasoning'
authors: Jingyang Yi, Jiazheng Wang, Sida Li
conference: "Arxiv"
year: 2025
bibkey: yi2025guiding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21370'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Agentic']
---
Recent models such as OpenAI o1 and DeepSeek-R1 have demonstrated strong performance on reasoning-intensive tasks by generating extended Chain-of-Thought (CoT) traces. While longer reasoning helps with thorough exploration of solution paths for complex problems, it also often leads to inefficient and redundant outputs--a phenomenon commonly described as overthinking. In this paper, we propose ShorterBetter, a simple yet effective reinforcement learning method that enables reasoning models to learn their own optimal CoT lengths without manual supervision. We define the Sample Optimal Length (SOL) as the length of the shortest correct response among multiple generations, which serves as a dynamic reward signal to guide the model toward efficient reasoning. Applied to DeepSeek-Distill-Qwen-1.5B/7B as base models, ShorterBetter achieves 50%-80% reduction in output lengths in both in-domain and out-of-domain reasoning tasks while maintaining accuracy. Our reasoning trace analysis shows that ShorterBetter refines the structure of the reasoning traces by reducing unnecessary repetition, excessive self-verification, and over-exploration of alternatives.
