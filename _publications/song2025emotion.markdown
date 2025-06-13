---
layout: publication
title: 'Emotion-o1: Adaptive Long Reasoning For Emotion Understanding In Llms'
authors: Changhao Song, Yazhou Zhang, Peng Zhang
conference: "Arxiv"
year: 2025
bibkey: song2025emotion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22548"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Emotion understanding includes basic tasks (e.g., sentiment/emotion classification) and advanced tasks (e.g., sarcasm/humor detection). Current methods rely on fixed-length CoT reasoning, failing to adapt to the varying complexity of emotions. We propose a task-adaptive reasoning framework that employs DeepSeek-R1 to generate variable-length reasoning chains for different emotion tasks. By combining fine-tuning with reinforcement learning, we design a composite reward function that balances four objectives: prediction accuracy, adaptive reasoning depth control, structural diversity in reasoning paths, and suppression of repetitive logic. This approach achieves dynamic context-sensitive inference while enabling LLMs to autonomously develop deep reasoning capabilities. Experimental results demonstrate consistent improvements in both Acc and F1 scores across four tasks: emotion, sentiment, humor, and sarcasm. Notably, peak enhancements reached 3.56% F1 (2.76% Acc) for basic tasks and 37.95% F1 (23.14% Acc) for advanced tasks. Our work bridges rigid CoT reasoning and emotional complexity through adaptive-depth analysis.
