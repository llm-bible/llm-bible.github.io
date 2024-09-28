---
layout: publication
title: Adversarial Tuning Defending Against Jailbreak Attacks for LLMs
authors: Liu Fan, Xu Zhao, Liu Hao
conference: "Arxiv"
year: 2024
bibkey: liu2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06622"}
tags: ['ARXIV', 'Pretraining Methods']
---
Although safely enhanced Large Language Models (LLMs) have achieved remarkable success in tackling various complex tasks in a zero-shot manner they remain susceptible to jailbreak attacks particularly the unknown jailbreak attack. To enhance LLMs generalized defense capabilities we propose a two-stage adversarial tuning framework which generates adversarial prompts to explore worst-case scenarios by optimizing datasets containing pairs of adversarial prompts and their safe responses. In the first stage we introduce the hierarchical meta-universal adversarial prompt learning to efficiently and effectively generate token-level adversarial prompts. In the second stage we propose the automatic adversarial prompt learning to iteratively refine semantic-level adversarial prompts further enhancing LLMs defense capabilities. We conducted comprehensive experiments on three widely used jailbreak datasets comparing our framework with six defense baselines under five representative attack scenarios. The results underscore the superiority of our proposed methods. Furthermore our adversarial tuning framework exhibits empirical generalizability across various attack strategies and target LLMs highlighting its potential as a transferable defense mechanism.
