---
layout: publication
title: 'Noise Injection Systemically Degrades Large Language Model Safety Guardrails'
authors: Prithviraj Singh Shahani, Matthias Scheutz
conference: "Arxiv"
year: 2025
bibkey: shahani2025noise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13500'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Safety guardrails in large language models (LLMs) are a critical component in preventing harmful outputs. Yet, their resilience under perturbation remains poorly understood. In this paper, we investigate the robustness of safety fine-tuning in LLMs by systematically injecting Gaussian noise into model activations. We show across multiple open-weight models that (1) Gaussian noise raises harmful-output rates (p < 0.001) by up to 27%, (2) that deeper safety fine-tuning affords no extra protection, and (3) that chain-of-thought reasoning remains largely intact. The findings reveal critical vulnerabilities in current safety alignment techniques and highlight the potential of reasoning-based and reinforcement learning approaches as promising direction for developing more robust AI safety systems. These results have important implications for real-world deployment of LLMs in safety-critical applications as these results imply that widely-deployed safety tuning methods can fail even without adversarial prompts.
