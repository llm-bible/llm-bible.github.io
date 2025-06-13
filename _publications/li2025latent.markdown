---
layout: publication
title: 'LARGO: Latent Adversarial Reflection Through Gradient Optimization For Jailbreaking Llms'
authors: Ran Li, Hao Wang, Chengzhi Mao
conference: "Arxiv"
year: 2025
bibkey: li2025latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10838"}
tags: ['Security', 'Agentic', 'Efficiency and Optimization', 'Prompting']
---
Efficient red-teaming method to uncover vulnerabilities in Large Language Models (LLMs) is crucial. While recent attacks often use LLMs as optimizers, the discrete language space make gradient-based methods struggle. We introduce LARGO (Latent Adversarial Reflection through Gradient Optimization), a novel latent self-reflection attack that reasserts the power of gradient-based optimization for generating fluent jailbreaking prompts. By operating within the LLM's continuous latent space, LARGO first optimizes an adversarial latent vector and then recursively call the same LLM to decode the latent into natural language. This methodology yields a fast, effective, and transferable attack that produces fluent and stealthy prompts. On standard benchmarks like AdvBench and JailbreakBench, LARGO surpasses leading jailbreaking techniques, including AutoDAN, by 44 points in attack success rate. Our findings demonstrate a potent alternative to agentic LLM prompting, highlighting the efficacy of interpreting and attacking LLM internals through gradient optimization.
