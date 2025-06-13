---
layout: publication
title: 'Inflvg: Reinforce Inference-time Consistent Long Video Generation With GRPO'
authors: Xueji Fang, Liyuan Ma, Zhiyang Chen, Mingyuan Zhou, Guo-jun Qi
conference: "Arxiv"
year: 2025
bibkey: fang2025reinforce
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17574'}
  - {name: "Code", url: 'https://github.com/MAPLE-AIGC/InfLVG'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'Efficiency and Optimization', 'GPT', 'Tools', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in text-to-video generation, particularly with autoregressive models, have enabled the synthesis of high-quality videos depicting individual scenes. However, extending these models to generate long, cross-scene videos remains a significant challenge. As the context length grows during autoregressive decoding, computational costs rise sharply, and the model's ability to maintain consistency and adhere to evolving textual prompts deteriorates. We introduce InfLVG, an inference-time framework that enables coherent long video generation without requiring additional long-form video data. InfLVG leverages a learnable context selection policy, optimized via Group Relative Policy Optimization (GRPO), to dynamically identify and retain the most semantically relevant context throughout the generation process. Instead of accumulating the entire generation history, the policy ranks and selects the top-\\(K\\) most contextually relevant tokens, allowing the model to maintain a fixed computational budget while preserving content consistency and prompt alignment. To optimize the policy, we design a hybrid reward function that jointly captures semantic alignment, cross-scene consistency, and artifact reduction. To benchmark performance, we introduce the Cross-scene Video Benchmark (CsVBench) along with an Event Prompt Set (EPS) that simulates complex multi-scene transitions involving shared subjects and varied actions/backgrounds. Experimental results show that InfLVG can extend video length by up to 9\\(\times\\), achieving strong consistency and semantic fidelity across scenes. Our code is available at https://github.com/MAPLE-AIGC/InfLVG.
