---
layout: publication
title: 'Shadowcot: Cognitive Hijacking For Stealthy Reasoning Backdoors In Llms'
authors: Gejian Zhao, Hanzhou Wu, Xinpeng Zhang, Athanasios V. Vasilakos
conference: "Arxiv"
year: 2025
bibkey: zhao2025cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05605"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'Attention Mechanism']
---
Chain-of-Thought (CoT) enhances an LLM's ability to perform complex reasoning
tasks, but it also introduces new security issues. In this work, we present
ShadowCoT, a novel backdoor attack framework that targets the internal
reasoning mechanism of LLMs. Unlike prior token-level or prompt-based attacks,
ShadowCoT directly manipulates the model's cognitive reasoning path, enabling
it to hijack multi-step reasoning chains and produce logically coherent but
adversarial outcomes. By conditioning on internal reasoning states, ShadowCoT
learns to recognize and selectively disrupt key reasoning steps, effectively
mounting a self-reflective cognitive attack within the target model. Our
approach introduces a lightweight yet effective multi-stage injection pipeline,
which selectively rewires attention pathways and perturbs intermediate
representations with minimal parameter overhead (only 0.15% updated). ShadowCoT
further leverages reinforcement learning and reasoning chain pollution (RCP) to
autonomously synthesize stealthy adversarial CoTs that remain undetectable to
advanced defenses. Extensive experiments across diverse reasoning benchmarks
and LLMs show that ShadowCoT consistently achieves high Attack Success Rate
(94.4%) and Hijacking Success Rate (88.4%) while preserving benign performance.
These results reveal an emergent class of cognition-level threats and highlight
the urgent need for defenses beyond shallow surface-level consistency.
