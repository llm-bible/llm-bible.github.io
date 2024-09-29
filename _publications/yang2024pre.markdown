---
layout: publication
title: Pre45;trained Language Models Improve The Few45;shot Prompt Ability Of Decision Transformer
authors: Yang Yu, Xu Pan
conference: "Arxiv"
year: 2024
bibkey: yang2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01402"}
tags: ['Agentic', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Decision Transformer (DT) has emerged as a promising class of algorithms in offline reinforcement learning (RL) tasks leveraging pre45;collected datasets and Transformers capability to model long sequences. Recent works have demonstrated that using parts of trajectories from training tasks as prompts in DT enhances its performance on unseen tasks giving rise to Prompt45;DT methods. However collecting data from specific environments can be both costly and unsafe in many scenarios leading to suboptimal performance and limited few45;shot prompt abilities due to the data45;hungry nature of Transformer45;based models. Additionally the limited datasets used in pre45;training make it challenging for Prompt45;DT type of methods to distinguish between various RL tasks through prompts alone. To address these challenges we introduce the Language model45;initialized Prompt Decision Transformer (LPDT) which leverages pre45;trained language models for meta45;RL tasks and fine45;tunes the model using Low45;rank Adaptation (LoRA). We further incorporate prompt regularization to effectively differentiate between tasks based on prompt feature representations. Our approach integrates pre45;trained language model and RL tasks seamlessly. Extensive empirical studies demonstrate that initializing with a pre45;trained language model significantly enhances the performance of Prompt45;DT on unseen tasks compared to baseline methods.
