---
layout: publication
title: Dialog Action45;aware Transformer For Dialog Policy Learning
authors: Wang Huimin, Kwan Wai-chung, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: wang2023dialog
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02240"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent works usually address Dialog policy learning DPL by training a reinforcement learning (RL) agent to determine the best dialog action. However existing works on deep RL require a large volume of agent45;user interactions to achieve acceptable performance. In this paper we propose to make full use of the plain text knowledge from the pre45;trained language model to accelerate the RL agents learning speed. Specifically we design a dialog action45;aware transformer encoder (DaTrans) which integrates a new fine45;tuning procedure named masked last action task to encourage DaTrans to be dialog45;aware and distils action45;specific features. Then DaTrans is further optimized in an RL setting with ongoing interactions and evolves through exploration in the dialog action space toward maximizing long45;term accumulated rewards. The effectiveness and efficiency of the proposed model are demonstrated with both simulator evaluation and human evaluation.
