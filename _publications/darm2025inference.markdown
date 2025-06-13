---
layout: publication
title: 'Inference-time Intervention In Large Language Models For Reliable Requirement Verification'
authors: Paul Darm, James Xie, Annalisa Riccardi
conference: "Arxiv"
year: 2025
bibkey: darm2025inference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14130'}
tags: ['Attention Mechanism', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Steering the behavior of Large Language Models (LLMs) remains a challenge,
particularly in engineering applications where precision and reliability are
critical. While fine-tuning and prompting methods can modify model behavior,
they lack the dynamic and exact control necessary for engineering applications.
Inference-time intervention techniques provide a promising alternative,
allowing targeted adjustments to LLM outputs. In this work, we demonstrate how
interventions enable fine-grained control for automating the usually
time-intensive requirement verification process in Model-Based Systems
Engineering (MBSE). Using two early-stage Capella SysML models of space
missions with associated requirements, we apply the intervened LLMs to reason
over a graph representation of the model to determine whether a requirement is
fulfilled. Our method achieves robust and reliable outputs, significantly
improving over both a baseline model and a fine-tuning approach. By identifying
and modifying as few as one to three specialised attention heads, we can
significantly change the model's behavior. When combined with self-consistency,
this allows us to achieve perfect precision on our holdout test set.
