---
layout: publication
title: 'Improving Llm-generated Code Quality With GRPO'
authors: Maxime Robeyns, Laurence Aitchison
conference: "Arxiv"
year: 2025
bibkey: robeyns2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02211"}
tags: ['Responsible AI', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Applications']
---
Large Language Models (LLMs) are gaining widespread use for code generation. Recent training procedures use execution feedback as a reward signal, typically focusing on the functional correctness of the code, using unit test pass rate as a reward signal. However, this reward signal fails to capture notions of maintainability, quality and safety of the code produced. We address this under-explored area and develop a comprehensive library to quantify various aspects of code quality, and use it as a reward in GRPO. We find GRPO increases code quality according to this measure, which is confirmed by expert, blinded human annotators.
