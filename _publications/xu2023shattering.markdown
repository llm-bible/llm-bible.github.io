---
layout: publication
title: 'Shattering The Agent-environment Interface For Fine-tuning Inclusive Language Models'
authors: Xu Wanqiao, Dong Shi, Arumugam Dilip, Van Roy Benjamin
conference: "Arxiv"
year: 2023
bibkey: xu2023shattering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11455"}
tags: ['Agentic', 'Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
A centerpiece of the ever-popular reinforcement learning from human feedback (RLHF) approach to fine-tuning autoregressive language models is the explicit training of a reward model to emulate human feedback distinct from the language model itself. This reward model is then coupled with policy-gradient methods to dramatically improve the alignment between language model outputs and desired responses. In this work we adopt a novel perspective wherein a pre-trained language model is itself simultaneously a policy reward function and transition function. An immediate consequence of this is that reward learning and language model fine-tuning can be performed jointly and directly without requiring any further downstream policy optimization. While this perspective does indeed break the traditional agent-environment interface we nevertheless maintain that there can be enormous statistical benefits afforded by bringing to bear traditional algorithmic concepts from reinforcement learning. Our experiments demonstrate one concrete instance of this through efficient exploration based on the representation and resolution of epistemic uncertainty. In order to illustrate these ideas in a transparent manner we restrict attention to a simple didactic data generating process and leave for future work extension to systems of practical scale.
