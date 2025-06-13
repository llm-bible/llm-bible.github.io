---
layout: publication
title: 'Right Question Is Already Half The Answer: Fully Unsupervised LLM Reasoning Incentivization'
authors: Qingyang Zhang, Haitao Wu, Changqing Zhang, Peilin Zhao, Yatao Bian
conference: "Arxiv"
year: 2025
bibkey: zhang2025right
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05812"}
  - {name: "Code", url: "https://github.com/QingyangZhang/EMPO"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Existing methods to enhance the reasoning capability of large language models predominantly rely on supervised fine-tuning (SFT) followed by reinforcement learning (RL) on reasoning-specific data. These approaches critically depend on external supervisions--such as labeled reasoning traces, verified golden answers, or pre-trained reward models. In this work, we propose Entropy Minimized Policy Optimization (\ours), which makes an early attempt at fully unsupervised LLM reasoning incentivization. By continuously minimizing the predictive entropy of LLMs on unlabeled questions in a latent semantic space, \ours achieves competitive performance compared to supervised counterparts on both mathematical and free-form natural reasoning tasks. Specifically, without any supervised signals, \ours boosts the accuracy of Qwen2.5-Math-7B Base from 30.7% to 48.1% on mathematical benchmarks and improves the accuracy of Qwen2.5-7B Base from 32.1% to 50.1% on MMLU-Pro. Primary experiments and analysis are also provided to interpret the effectiveness of \ours. Code is available at https://github.com/QingyangZhang/EMPO.
