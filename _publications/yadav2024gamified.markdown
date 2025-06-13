---
layout: publication
title: 'Gamified Crowd-sourcing Of High-quality Data For Visual Fine-tuning'
authors: Shashank Yadav, Rohan Tomar, Garvit Jain, Chirag Ahooja, Shubham Chaudhary, Charles Elkan
conference: "Arxiv"
year: 2024
bibkey: yadav2024gamified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04038"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
This paper introduces Gamified Adversarial Prompting (GAP), a framework that
crowd-sources high-quality data for visual instruction tuning of large
multimodal models. GAP transforms the data collection process into an engaging
game, incentivizing players to provide fine-grained, challenging questions and
answers that target gaps in the model's knowledge. Our contributions include
(1) an approach to capture question-answer pairs from humans that directly
address weaknesses in a model's knowledge, (2) a method for evaluating and
rewarding players that successfully incentivizes them to provide high-quality
submissions, and (3) a scalable, gamified platform that succeeds in collecting
this data from over 50,000 participants in just a few weeks. Our implementation
of GAP has significantly improved the accuracy of a small multimodal model,
namely MiniCPM-Llama3-V-2.5-8B, increasing its GPT score from 0.147 to 0.477 on
our dataset, approaching the benchmark set by the much larger GPT-4V. Moreover,
we demonstrate that the data generated using MiniCPM-Llama3-V-2.5-8B also
enhances its performance across other benchmarks, and exhibits cross-model
benefits. Specifically, the same data improves the performance of QWEN2-VL-2B
and QWEN2-VL-7B on the same multiple benchmarks.
