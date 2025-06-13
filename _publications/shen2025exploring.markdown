---
layout: publication
title: 'Exploring Data Scaling Trends And Effects In Reinforcement Learning From Human Feedback'
authors: Wei Shen, Guanlin Liu, Zheng Wu, Ruofei Zhu, Qingping Yang, Chao Xin, Yu Yue, Lin Yan
conference: "Arxiv"
year: 2025
bibkey: shen2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22230"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Fine-Tuning', 'Prompting']
---
Reinforcement Learning from Human Feedback (RLHF) is crucial for aligning
large language models with human preferences. While recent research has focused
on algorithmic improvements, the importance of prompt-data construction has
been overlooked. This paper addresses this gap by exploring data-driven
bottlenecks in RLHF performance scaling, particularly reward hacking and
decreasing response diversity. We introduce a hybrid reward system combining
reasoning task verifiers (RTV) and a generative reward model (GenRM) to
mitigate reward hacking. We also propose a novel prompt-selection method,
Pre-PPO, to maintain response diversity and enhance learning effectiveness.
Additionally, we find that prioritizing mathematical and coding tasks early in
RLHF training significantly improves performance. Experiments across two model
sizes validate our methods' effectiveness and scalability. Results show that
RTV is most resistant to reward hacking, followed by GenRM with ground truth,
and then GenRM with SFT Best-of-N responses. Our strategies enable rapid
capture of subtle task-specific distinctions, leading to substantial
improvements in overall RLHF performance. This work highlights the importance
of careful data construction and provides practical methods to overcome
performance barriers in RLHF.
