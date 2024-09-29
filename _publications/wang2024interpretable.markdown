---
layout: publication
title: Interpretable Preferences Via Multi45;objective Reward Modeling And Mixture45;of45;experts
authors: Wang Haoxiang, Xiong Wei, Xie Tengyang, Zhao Han, Zhang Tong
conference: "Arxiv"
year: 2024
bibkey: wang2024interpretable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12845"}
tags: ['Agentic', 'GPT', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Reinforcement learning from human feedback (RLHF) has emerged as the primary method for aligning large language models (LLMs) with human preferences. The RLHF process typically starts by training a reward model (RM) using human preference data. Conventional RMs are trained on pairwise responses to the same user request with relative ratings indicating which response humans prefer. The trained RM serves as a proxy for human preferences. However due to the black45;box nature of RMs their outputs lack interpretability as humans cannot intuitively understand why an RM thinks a response is good or not. As RMs act as human preference proxies we believe they should be human45;interpretable to ensure that their internal decision processes are consistent with human preferences and to prevent reward hacking in LLM alignment. To build RMs with interpretable preferences we propose a two45;stage approach i) train an Absolute45;Rating Multi45;Objective Reward Model (ArmoRM) with multi45;dimensional absolute45;rating data each dimension corresponding to a human45;interpretable objective (e.g. honesty verbosity safety); ii) employ a Mixture45;of45;Experts (MoE) strategy with a gating network that automatically selects the most suitable reward objectives based on the context. We efficiently trained an ArmoRM with Llama45;3 8B and a gating network consisting of a shallow MLP on top of the ArmoRM. Our trained model ArmoRM45;Llama345;8B obtains state45;of45;the45;art performance on RewardBench a benchmark evaluating RMs for language modeling. Notably the performance of our model surpasses the LLM45;as45;a45;judge method with GPT45;4 judges by a margin and approaches the performance of the much larger Nemotron45;4 340B reward model.
