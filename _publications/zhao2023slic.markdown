---
layout: publication
title: Slic-hf\: Sequence Likelihood Calibration With Human Feedback
authors: Zhao Yao, Joshi Rishabh, Liu Tianqi, Khalman Misha, Saleh Mohammad, Liu Peter J.
conference: "Arxiv"
year: 2023
bibkey: zhao2023slic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10425"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Learning from human feedback has been shown to be effective at aligning language models with human preferences. Past work has often relied on Reinforcement Learning from Human Feedback (RLHF) which optimizes the language model using reward scores assigned from a reward model trained on human preference data. In this work we show how the recently introduced Sequence Likelihood Calibration (SLiC) can also be used to effectively learn from human preferences (SLiC-HF). Furthermore we demonstrate this can be done with human feedback data collected for a different model similar to off-policy offline RL data. Automatic and human evaluation experiments on the TL;DR summarization task show that SLiC-HF significantly improves supervised fine-tuning baselines. Furthermore SLiC-HF presents a competitive alternative to the PPO RLHF implementation used in past work while being much simpler to implement easier to tune and more computationally efficient in practice.
