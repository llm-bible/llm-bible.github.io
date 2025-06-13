---
layout: publication
title: 'Why LLM Safety Guardrails Collapse After Fine-tuning: A Similarity Analysis Between Alignment And Fine-tuning Datasets'
authors: Lei Hsiung, Tianyu Pang, Yung-chen Tang, Linyue Song, Tsung-yi Ho, Pin-yu Chen, Yaoqing Yang
conference: "Arxiv"
year: 2025
bibkey: hsiung2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05346'}
tags: ['Security', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Recent advancements in large language models (LLMs) have underscored their vulnerability to safety alignment jailbreaks, particularly when subjected to downstream fine-tuning. However, existing mitigation strategies primarily focus on reactively addressing jailbreak incidents after safety guardrails have been compromised, removing harmful gradients during fine-tuning, or continuously reinforcing safety alignment throughout fine-tuning. As such, they tend to overlook a critical upstream factor: the role of the original safety-alignment data. This paper therefore investigates the degradation of safety guardrails through the lens of representation similarity between upstream alignment datasets and downstream fine-tuning tasks. Our experiments demonstrate that high similarity between these datasets significantly weakens safety guardrails, making models more susceptible to jailbreaks. Conversely, low similarity between these two types of datasets yields substantially more robust models and thus reduces harmfulness score by up to 10.33%. By highlighting the importance of upstream dataset design in the building of durable safety guardrails and reducing real-world vulnerability to jailbreak attacks, these findings offer actionable insights for fine-tuning service providers.
