---
layout: publication
title: V45;star Training Verifiers For Self45;taught Reasoners
authors: Hosseini Arian, Yuan Xingdi, Malkin Nikolay, Courville Aaron, Sordoni Alessandro, Agarwal Rishabh
conference: "Arxiv"
year: 2024
bibkey: hosseini2024v
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06457"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Common self45;improvement approaches for large language models (LLMs) such as STaR iteratively fine45;tune LLMs on self45;generated solutions to improve their problem45;solving ability. However these approaches discard the large amounts of incorrect solutions generated during this process potentially neglecting valuable information in such solutions. To address this shortcoming we propose V45;STaR that utilizes both the correct and incorrect solutions generated during the self45;improvement process to train a verifier using DPO that judges correctness of model45;generated solutions. This verifier is used at inference time to select one solution among many candidate solutions. Running V45;STaR for multiple iterations results in progressively better reasoners and verifiers delivering a 437; to 1737; test accuracy improvement over existing self45;improvement and verification approaches on common code generation and math reasoning benchmarks with LLaMA2 models.
