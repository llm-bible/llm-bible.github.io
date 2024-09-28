---
layout: publication
title: Pre-trained Language Models Improve the Few-shot Prompt Ability of Decision Transformer
authors: Yang Yu, Xu Pan
conference: "Arxiv"
year: 2024
bibkey: yang2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01402"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Transformer']
---
Decision Transformer (DT) has emerged as a promising class of algorithms in offline reinforcement learning (RL) tasks leveraging pre-collected datasets and Transformers capability to model long sequences. Recent works have demonstrated that using parts of trajectories from training tasks as prompts in DT enhances its performance on unseen tasks giving rise to Prompt-DT methods. However collecting data from specific environments can be both costly and unsafe in many scenarios leading to suboptimal performance and limited few-shot prompt abilities due to the data-hungry nature of Transformer-based models. Additionally the limited datasets used in pre-training make it challenging for Prompt-DT type of methods to distinguish between various RL tasks through prompts alone. To address these challenges we introduce the Language model-initialized Prompt Decision Transformer (LPDT) which leverages pre-trained language models for meta-RL tasks and fine-tunes the model using Low-rank Adaptation (LoRA). We further incorporate prompt regularization to effectively differentiate between tasks based on prompt feature representations. Our approach integrates pre-trained language model and RL tasks seamlessly. Extensive empirical studies demonstrate that initializing with a pre-trained language model significantly enhances the performance of Prompt-DT on unseen tasks compared to baseline methods.
