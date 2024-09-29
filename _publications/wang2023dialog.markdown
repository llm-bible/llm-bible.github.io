---
layout: publication
title: "Dialog Action-aware Transformer For Dialog Policy Learning"
authors: Wang Huimin, Kwan Wai-chung, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: wang2023dialog
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02240"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent works usually address Dialog policy learning DPL by training a reinforcement learning (RL) agent to determine the best dialog action. However existing works on deep RL require a large volume of agent-user interactions to achieve acceptable performance. In this paper we propose to make full use of the plain text knowledge from the pre-trained language model to accelerate the RL agents learning speed. Specifically we design a dialog action-aware transformer encoder (DaTrans) which integrates a new fine-tuning procedure named masked last action task to encourage DaTrans to be dialog-aware and distils action-specific features. Then DaTrans is further optimized in an RL setting with ongoing interactions and evolves through exploration in the dialog action space toward maximizing long-term accumulated rewards. The effectiveness and efficiency of the proposed model are demonstrated with both simulator evaluation and human evaluation.
