---
layout: publication
title: 'Aligning Dialogue Agents With Global Feedback Via Large Language Model Reward Decomposition'
authors: Dong Won Lee, Hae Won Park, Cynthia Breazeal, Louis-philippe Morency
conference: "Arxiv"
year: 2025
bibkey: lee2025aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15922"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
We propose a large language model based reward decomposition framework for aligning dialogue agents using only a single session-level feedback signal. We leverage the reasoning capabilities of a frozen, pretrained large language model (LLM) to infer fine-grained local implicit rewards by decomposing global, session-level feedback. Our first text-only variant prompts the LLM to perform reward decomposition using only the dialogue transcript. The second multimodal variant incorporates additional behavioral cues, such as pitch, gaze, and facial affect, expressed as natural language descriptions. These inferred turn-level rewards are distilled into a lightweight reward model, which we utilize for RL-based fine-tuning for dialogue generation. We evaluate both text-only and multimodal variants against state-of-the-art reward decomposition methods and demonstrate notable improvements in human evaluations of conversation quality, suggesting that LLMs are strong reward decomposers that obviate the need for manual reward shaping and granular human feedback.
