---
layout: publication
title: 'Refusal Direction Is Universal Across Safety-aligned Languages'
authors: Xinpeng Wang, Mingyang Wang, Yihong Liu, Hinrich Schütze, Barbara Plank
conference: "Arxiv"
year: 2025
bibkey: wang2025refusal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17306'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Refusal mechanisms in large language models (LLMs) are essential for ensuring safety. Recent research has revealed that refusal behavior can be mediated by a single direction in activation space, enabling targeted interventions to bypass refusals. While this is primarily demonstrated in an English-centric context, appropriate refusal behavior is important for any language, but poorly understood. In this paper, we investigate the refusal behavior in LLMs across 14 languages using PolyRefuse, a multilingual safety dataset created by translating malicious and benign English prompts into these languages. We uncover the surprising cross-lingual universality of the refusal direction: a vector extracted from English can bypass refusals in other languages with near-perfect effectiveness, without any additional fine-tuning. Even more remarkably, refusal directions derived from any safety-aligned language transfer seamlessly to others. We attribute this transferability to the parallelism of refusal vectors across languages in the embedding space and identify the underlying mechanism behind cross-lingual jailbreaks. These findings provide actionable insights for building more robust multilingual safety defenses and pave the way for a deeper mechanistic understanding of cross-lingual vulnerabilities in LLMs.
