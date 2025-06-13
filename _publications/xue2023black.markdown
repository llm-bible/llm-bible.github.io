---
layout: publication
title: 'Trojllm: A Black-box Trojan Prompt Attack On Large Language Models'
authors: Jiaqi Xue, Mengxin Zheng, Ting Hua, Yilin Shen, Yepeng Liu, Ladislau Boloni, Qian Lou
conference: "Arxiv"
year: 2023
bibkey: xue2023black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06815"}
  - {name: "Code", url: "https://github.com/UCF-ML-Research/TrojLLM"}
tags: ['Security', 'Model Architecture', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'GPT', 'Has Code', 'Prompting', 'Applications']
---
Large Language Models (LLMs) are progressively being utilized as machine
learning services and interface tools for various applications. However, the
security implications of LLMs, particularly in relation to adversarial and
Trojan attacks, remain insufficiently examined. In this paper, we propose
TrojLLM, an automatic and black-box framework to effectively generate universal
and stealthy triggers. When these triggers are incorporated into the input
data, the LLMs' outputs can be maliciously manipulated. Moreover, the framework
also supports embedding Trojans within discrete prompts, enhancing the overall
effectiveness and precision of the triggers' attacks. Specifically, we propose
a trigger discovery algorithm for generating universal triggers for various
inputs by querying victim LLM-based APIs using few-shot data samples.
Furthermore, we introduce a novel progressive Trojan poisoning algorithm
designed to generate poisoned prompts that retain efficacy and transferability
across a diverse range of models. Our experiments and results demonstrate
TrojLLM's capacity to effectively insert Trojans into text prompts in
real-world black-box LLM APIs including GPT-3.5 and GPT-4, while maintaining
exceptional performance on clean test sets. Our work sheds light on the
potential security risks in current models and offers a potential defensive
approach. The source code of TrojLLM is available at
https://github.com/UCF-ML-Research/TrojLLM.
