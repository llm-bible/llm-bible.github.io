---
layout: publication
title: 'Safety Is Not Only About Refusal: Reasoning-enhanced Fine-tuning For Interpretable LLM Safety'
authors: Yuyou Zhang, Miao Li, William Han, Yihang Yao, Zhepeng Cen, Ding Zhao
conference: "Arxiv"
year: 2025
bibkey: zhang2025safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05021"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) are vulnerable to jailbreak attacks that exploit
weaknesses in traditional safety alignment, which often relies on rigid refusal
heuristics or representation engineering to block harmful outputs. While they
are effective for direct adversarial attacks, they fall short of broader safety
challenges requiring nuanced, context-aware decision-making. To address this,
we propose Reasoning-enhanced Finetuning for interpretable LLM Safety
(Rational), a novel framework that trains models to engage in explicit safe
reasoning before response. Fine-tuned models leverage the extensive pretraining
knowledge in self-generated reasoning to bootstrap their own safety through
structured reasoning, internalizing context-sensitive decision-making. Our
findings suggest that safety extends beyond refusal, requiring context
awareness for more robust, interpretable, and adaptive responses. Reasoning is
not only a core capability of LLMs but also a fundamental mechanism for LLM
safety. Rational employs reasoning-enhanced fine-tuning, allowing it to reject
harmful prompts while providing meaningful and context-aware responses in
complex scenarios.
