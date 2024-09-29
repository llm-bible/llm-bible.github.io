---
layout: publication
title: Reft Reasoning With Reinforced Fine45;tuning
authors: Luong Trung Quoc, Zhang Xinbo, Jie Zhanming, Sun Peng, Jin Xiaoran, Li Hang
conference: "Arxiv"
year: 2024
bibkey: luong2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08967"}
tags: ['Agentic', 'Fine Tuning', 'Reinforcement Learning', 'Training Techniques']
---
One way to enhance the reasoning capability of Large Language Models (LLMs) is to conduct Supervised Fine45;Tuning (SFT) using Chain45;of45;Thought (CoT) annotations. This approach does not show sufficiently strong generalization ability however because the training only relies on the given CoT data. In math problem45;solving for example there is usually only one annotated reasoning path for each question in the training data. Intuitively it would be better for the algorithm to learn from multiple annotated reasoning paths given a question. To address this issue we propose a simple yet effective approach called Reinforced Fine45;Tuning (ReFT) to enhance the generalizability of learning LLMs for reasoning with math problem45;solving as an example. ReFT first warmups the model with SFT and then employs on45;line reinforcement learning specifically the PPO algorithm in this paper to further fine45;tune the model where an abundance of reasoning paths are automatically sampled given the question and the rewards are naturally derived from the ground45;truth answers. Extensive experiments on GSM8K MathQA and SVAMP datasets show that ReFT significantly outperforms SFT and the performance can be potentially further boosted by combining inference45;time strategies such as majority voting and re45;ranking. Note that ReFT obtains the improvement by learning from the same training questions as SFT without relying on extra or augmented training questions. This indicates a superior generalization ability for ReFT.
