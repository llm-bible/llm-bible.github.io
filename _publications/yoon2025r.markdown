---
layout: publication
title: 'R-TOFU: Unlearning In Large Reasoning Models'
authors: Sangyeon Yoon, Wonje Jeung, Albert No
conference: "Arxiv"
year: 2025
bibkey: yoon2025r
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15214"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning']
---
Large Reasoning Models (LRMs) embed private or copyrighted information not only in their final answers but also throughout multi-step chain-of-thought (CoT) traces, making reliable unlearning far more demanding than in standard LLMs. We introduce Reasoning-TOFU (R-TOFU), the first benchmark tailored to this setting. R-TOFU augments existing unlearning tasks with realistic CoT annotations and provides step-wise metrics that expose residual knowledge invisible to answer-level checks. Using R-TOFU, we carry out a comprehensive comparison of gradient-based and preference-optimization baselines and show that conventional answer-only objectives leave substantial forget traces in reasoning. We further propose Reasoned IDK, a preference-optimization variant that preserves coherent yet inconclusive reasoning, achieving a stronger balance between forgetting efficacy and model utility than earlier refusal styles. Finally, we identify a failure mode: decoding variants such as ZeroThink and LessThink can still reveal forgotten content despite seemingly successful unlearning, emphasizing the need to evaluate models under diverse decoding settings. Together, the benchmark, analysis, and new baseline establish a systematic foundation for studying and improving unlearning in LRMs while preserving their reasoning capabilities.
