---
layout: publication
title: 'Keep The General, Inject The Specific: Structured Dialogue Fine-tuning For Knowledge Injection Without Catastrophic Forgetting'
authors: Yijie Hong, Xiaofei Yin, Xinzhong Wang, Yi Tu, Ya Guo, Sufeng Duan, Weiqiang Wang, Lingyong Fang, Depeng Wang, Huijia Zhu
conference: "Arxiv"
year: 2025
bibkey: hong2025keep
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00029'}
tags: ['Training Techniques', 'Tools', 'Merging', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
Large Vision Language Models have demonstrated impressive versatile
capabilities through extensive multimodal pre-training, but face significant
limitations when incorporating specialized knowledge domains beyond their
training distribution. These models struggle with a fundamental dilemma: direct
adaptation approaches that inject domain-specific knowledge often trigger
catastrophic forgetting of foundational visual-linguistic abilities. We
introduce Structured Dialogue Fine-Tuning (SDFT), an effective approach that
effectively injects domain-specific knowledge while minimizing catastrophic
forgetting. Drawing inspiration from supervised fine-tuning in LLMs and
subject-driven personalization in text-to-image diffusion models, our method
employs a three-phase dialogue structure: Foundation Preservation reinforces
pre-trained visual-linguistic alignment through caption tasks; Contrastive
Disambiguation introduces carefully designed counterfactual examples to
maintain semantic boundaries; and Knowledge Specialization embeds specialized
information through chain-of-thought reasoning. Experimental results across
multiple domains confirm SDFT's effectiveness in balancing specialized
knowledge acquisition with general capability retention. Our key contributions
include a data-centric dialogue template that balances foundational alignment
with targeted knowledge integration, a weighted multi-turn supervision
framework, and comprehensive evaluation across diverse knowledge types.
