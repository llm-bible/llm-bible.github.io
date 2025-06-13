---
layout: publication
title: 'A Long Way To Go: Investigating Length Correlations In RLHF'
authors: Prasann Singhal, Tanya Goyal, Jiacheng Xu, Greg Durrett
conference: "Arxiv"
year: 2023
bibkey: singhal2023long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.03716'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Reinforcement Learning', 'Ethics and Bias']
---
Great success has been reported using Reinforcement Learning from Human
Feedback (RLHF) to align large language models, with open preference datasets
enabling wider experimentation, particularly for "helpfulness" in tasks like
dialogue and web question answering. Alongside these improvements, however,
RLHF also often drives models to produce longer outputs. This paper
demonstrates, on three diverse settings, that optimizing for response length
is, much more than previously thought, a significant factor behind RLHF.
Studying the strategies RL optimization uses to maximize reward, we find
improvements in reward to largely be driven by increasing response length,
instead of other features. Indeed, we find that even a purely length-based
reward reproduces most downstream RLHF improvements over supervised fine-tuned
models. Testing a comprehensive set of length-countering interventions, we
identify the dominant source of these biases to be reward models, which, by
studying training dynamics, we find are non-robust and easily influenced by
length biases in preference data.
