---
layout: publication
title: Bag of Tricks Benchmarking of Jailbreak Attacks on LLMs
authors: Xu Zhao, Liu Fan, Liu Hao
conference: "Arxiv"
year: 2024
bibkey: xu2024bag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09324"}
  - {name: "Code", url: "https://github.com/usail-hkust/Bag_of_Tricks_for_LLM_Jailbreaking"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Although Large Language Models (LLMs) have demonstrated significant capabilities in executing complex tasks in a zero-shot manner they are susceptible to jailbreak attacks and can be manipulated to produce harmful outputs. Recently a growing body of research has categorized jailbreak attacks into token-level and prompt-level attacks. However previous work primarily overlooks the diverse key factors of jailbreak attacks with most studies concentrating on LLM vulnerabilities and lacking exploration of defense-enhanced LLMs. To address these issues we evaluate the impact of various attack settings on LLM performance and provide a baseline benchmark for jailbreak attacks encouraging the adoption of a standardized evaluation framework. Specifically we evaluate the eight key factors of implementing jailbreak attacks on LLMs from both target-level and attack-level perspectives. We further conduct seven representative jailbreak attacks on six defense methods across two widely used datasets encompassing approximately 320 experiments with about 50000 GPU hours on A800-80G. Our experimental results highlight the need for standardized benchmarking to evaluate these attacks on defense-enhanced LLMs. Our code is available at https://github.com/usail-hkust/Bag_of_Tricks_for_LLM_Jailbreaking.
