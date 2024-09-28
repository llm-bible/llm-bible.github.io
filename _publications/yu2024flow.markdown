---
layout: publication
title: Flow of Reasoning Efficient Training of LLM Policy with Divergent Thinking
authors: Yu Fangxu, Jiang Lai, Kang Haoqiang, Hao Shibo, Qin Lianhui
conference: "Arxiv"
year: 2024
bibkey: yu2024flow
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05673"}
  - {name: "Code", url: "https://github.com/Yu-Fangxu/FoR"}
tags: ['ARXIV', 'Agentic', 'Fine Tuning', 'Has Code', 'LLM', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Divergent thinking the cognitive process of generating diverse solutions is a hallmark of human creativity and problem-solving. For machines sampling diverse solution trajectories in complex reasoning problems is crucial for robust outcomes data augmentation and enhanced model generalization. Large language models (LLMs) often struggle with generating high-quality diverse reasoning. While supervised fine-tuning helps with quality it requires extensive supervision data to capture the full diversity of solutions. Alternatively reinforcement learning methods like PPO aim to find limited highest-reward solutions while neglecting the solution diversity akin to convergent thinking. To address these limitations we propose Flow of Reasoning (FoR) -- an efficient LLM training approach enabling diverse reasoning with minimal data. FoR formulates multi-step LLM reasoning as a Markovian flow from an initial state to terminal states. The formulation allows to adapt principled GFlowNet approaches to train the LLM as a policy which is able to sample multiple reasoning paths with probabilities proportional to the unnormalized reward. Empirical results show that with limited training data (e.g. 15 examples) FoR can discover diverse high-quality solutions that excel greatly beyond current state-of-the-art methods across three tasks including embodied reasoning (BlocksWorld) math puzzle solving (Game24) and logical reasoning (PrOntoQA). Code is available at https://github.com/Yu-Fangxu/FoR.
