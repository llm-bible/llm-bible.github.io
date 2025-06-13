---
layout: publication
title: 'V-star: Training Verifiers For Self-taught Reasoners'
authors: Arian Hosseini, Xingdi Yuan, Nikolay Malkin, Aaron Courville, Alessandro Sordoni, Rishabh Agarwal
conference: "Arxiv"
year: 2024
bibkey: hosseini2024v
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06457"}
tags: ['Training Techniques', 'Applications', 'Reinforcement Learning']
---
Common self-improvement approaches for large language models (LLMs), such as
STaR, iteratively fine-tune LLMs on self-generated solutions to improve their
problem-solving ability. However, these approaches discard the large amounts of
incorrect solutions generated during this process, potentially neglecting
valuable information in such solutions. To address this shortcoming, we propose
V-STaR that utilizes both the correct and incorrect solutions generated during
the self-improvement process to train a verifier using DPO that judges
correctness of model-generated solutions. This verifier is used at inference
time to select one solution among many candidate solutions. Running V-STaR for
multiple iterations results in progressively better reasoners and verifiers,
delivering a 4% to 17% test accuracy improvement over existing self-improvement
and verification approaches on common code generation and math reasoning
benchmarks with LLaMA2 models.
