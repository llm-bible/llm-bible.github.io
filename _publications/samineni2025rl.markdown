---
layout: publication
title: 'RL In Name Only? Analyzing The Structural Assumptions In RL Post-training For Llms'
authors: Soumya Rani Samineni, Durgesh Kalwar, Karthik Valmeekam, Kaya Stechly, Subbarao Kambhampati
conference: "Arxiv"
year: 2025
bibkey: samineni2025rl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13697"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Attention Mechanism']
---
Reinforcement learning-based post-training of large language models (LLMs) has recently gained attention, particularly following the release of DeepSeek R1, which applied GRPO for fine-tuning. Amid the growing hype around improved reasoning abilities attributed to RL post-training, we critically examine the formulation and assumptions underlying these methods. We start by highlighting the popular structural assumptions made in modeling LLM training as a Markov Decision Process (MDP), and show how they lead to a degenerate MDP that doesn't quite need the RL/GRPO apparatus. The two critical structural assumptions include (1) making the MDP states be just a concatenation of the actions-with states becoming the context window and the actions becoming the tokens in LLMs and (2) splitting the reward of a state-action trajectory uniformly across the trajectory. Through a comprehensive analysis, we demonstrate that these simplifying assumptions make the approach effectively equivalent to an outcome-driven supervised learning. Our experiments on benchmarks including GSM8K and Countdown using Qwen-2.5 base models show that iterative supervised fine-tuning, incorporating both positive and negative samples, achieves performance comparable to GRPO-based training. We will also argue that the structural assumptions indirectly incentivize the RL to generate longer sequences of intermediate tokens-which in turn feeds into the narrative of "RL generating longer thinking traces." While RL may well be a very useful technique for improving the reasoning abilities of LLMs, our analysis shows that the simplistic structural assumptions made in modeling the underlying MDP render the popular LLM RL frameworks and their interpretations questionable.
