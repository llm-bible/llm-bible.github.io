---
layout: publication
title: 'Direct Advantage Regression: Aligning Llms With Online AI Reward'
authors: Li He, He Zhao, Stephen Wan, Dadong Wang, Lina Yao, Tongliang Liu
conference: "Arxiv"
year: 2025
bibkey: he2025direct
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14177'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Online AI Feedback (OAIF) presents a promising alternative to Reinforcement
Learning from Human Feedback (RLHF) by utilizing online AI preference in
aligning language models (LLMs). However, the straightforward replacement of
humans with AI deprives LLMs from learning more fine-grained AI supervision
beyond binary signals. In this paper, we propose Direct Advantage Regression
(DAR), a simple alignment algorithm using online AI reward to optimize policy
improvement through weighted supervised fine-tuning. As an RL-free approach,
DAR maintains theoretical consistency with online RLHF pipelines while
significantly reducing implementation complexity and improving learning
efficiency. Our empirical results underscore that AI reward is a better form of
AI supervision consistently achieving higher human-AI agreement as opposed to
AI preference. Additionally, evaluations using GPT-4-Turbo and MT-bench show
that DAR outperforms both OAIF and online RLHF baselines.
