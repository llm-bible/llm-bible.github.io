---
layout: publication
title: V-star: Training Verifiers For Self-taught Reasoners
authors: Hosseini Arian, Yuan Xingdi, Malkin Nikolay, Courville Aaron, Sordoni Alessandro, Agarwal Rishabh
conference: "Arxiv"
year: 2024
bibkey: hosseini2024v
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06457"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Common self-improvement approaches for large language models (LLMs) such as STaR iteratively fine-tune LLMs on self-generated solutions to improve their problem-solving ability. However these approaches discard the large amounts of incorrect solutions generated during this process potentially neglecting valuable information in such solutions. To address this shortcoming we propose V-STaR that utilizes both the correct and incorrect solutions generated during the self-improvement process to train a verifier using DPO that judges correctness of model-generated solutions. This verifier is used at inference time to select one solution among many candidate solutions. Running V-STaR for multiple iterations results in progressively better reasoners and verifiers delivering a 437; to 1737; test accuracy improvement over existing self-improvement and verification approaches on common code generation and math reasoning benchmarks with LLaMA2 models.
