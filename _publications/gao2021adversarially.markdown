---
layout: publication
title: An Adversarially-Learned Turing Test for Dialog Generation Models
authors: Gao Xiang, Zhang Yizhe, Galley Michel, Dolan Bill
conference: "Arxiv"
year: 2021
bibkey: gao2021adversarially
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.08231"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
The design of better automated dialogue evaluation metrics offers the potential of accelerate evaluation research on conversational AI. However existing trainable dialogue evaluation models are generally restricted to classifiers trained in a purely supervised manner which suffer a significant risk from adversarial attacking (e.g. a nonsensical response that enjoys a high classification score). To alleviate this risk we propose an adversarial training approach to learn a robust model ATT (Adversarial Turing Test) that discriminates machine-generated responses from human-written replies. In contrast to previous perturbation-based methods our discriminator is trained by iteratively generating unrestricted and diverse adversarial examples using reinforcement learning. The key benefit of this unrestricted adversarial training approach is allowing the discriminator to improve robustness in an iterative attack-defense game. Our discriminator shows high accuracy on strong attackers including DialoGPT and GPT-3.
