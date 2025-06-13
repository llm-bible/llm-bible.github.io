---
layout: publication
title: 'Activation Steering In Neural Theorem Provers'
authors: Shashank Kirtania
conference: "Arxiv"
year: 2025
bibkey: kirtania2025activation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15507"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown promise in proving formal theorems using proof assistants like Lean. However, current state of the art language models struggles to predict next step in proofs leading practitioners to use different sampling techniques to improve LLMs capabilities. We observe that the LLM is capable of predicting the correct tactic; however, it faces challenges in ranking it appropriately within the set of candidate tactics, affecting the overall selection process. To overcome this hurdle, we use activation steering to guide LLMs responses to improve the generations at the time of inference. Our results suggest that activation steering offers a promising lightweight alternative to specialized fine-tuning for enhancing theorem proving capabilities in LLMs, particularly valuable in resource-constrained environments.
