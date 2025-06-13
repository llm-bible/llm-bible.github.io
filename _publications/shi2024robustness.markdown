---
layout: publication
title: 'Robustness-aware Automatic Prompt Optimization'
authors: Zeru Shi, Zhenting Wang, Yongye Su, Weidi Luo, Hang Gao, Fan Yang, Ruixiang Tang, Yongfeng Zhang
conference: "Arxiv"
year: 2024
bibkey: shi2024robustness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18196"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'RAG', 'Prompting']
---
The performance of Large Language Models (LLMs) depends on the quality of
prompts and the semantic and structural integrity of the input data. However,
existing prompt generation methods primarily focus on well-structured input
data, often neglecting the impact of perturbed inputs on prompt effectiveness.
To address this limitation, we propose BATprompt (By Adversarial Training
prompt), a novel method for prompt generation designed to withstand input
perturbations (such as typos in the input). Inspired by adversarial training
techniques, BATprompt demonstrates strong performance on a variety of perturbed
tasks through a two-step process: adversarial perturbation and iterative
optimization on unperturbed input via LLM. Unlike conventional adversarial
attack methods, BATprompt does not need access to model parameters and
gradients. Instead, BATprompt leverages the advanced reasoning, language
understanding and self reflection capabilities of LLMs to simulate gradients,
guiding the generation of adversarial perturbations and optimizing prompt
performance. We evaluate BATprompt on multiple datasets across both language
understanding and generation tasks. The results indicate that BATprompt
outperforms existing prompt generation methods, delivering superior robustness
and performance under diverse perturbation scenarios.
