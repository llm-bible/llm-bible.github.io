---
layout: publication
title: 'Intrinsic Model Weaknesses: How Priming Attacks Unveil Vulnerabilities In Large Language Models'
authors: Yuyi Huang, Runzhe Zhan, Derek F. Wong, Lidia S. Chao, Ailin Tao
conference: "Arxiv"
year: 2025
bibkey: huang2025intrinsic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16491"}
tags: ['GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Attention Mechanism']
---
Large language models (LLMs) have significantly influenced various industries
but suffer from a critical flaw, the potential sensitivity of generating
harmful content, which poses severe societal risks. We developed and tested
novel attack strategies on popular LLMs to expose their vulnerabilities in
generating inappropriate content. These strategies, inspired by psychological
phenomena such as the "Priming Effect", "Safe Attention Shift", and "Cognitive
Dissonance", effectively attack the models' guarding mechanisms. Our
experiments achieved an attack success rate (ASR) of 100% on various
open-source models, including Meta's Llama-3.2, Google's Gemma-2, Mistral's
Mistral-NeMo, Falcon's Falcon-mamba, Apple's DCLM, Microsoft's Phi3, and Qwen's
Qwen2.5, among others. Similarly, for closed-source models such as OpenAI's
GPT-4o, Google's Gemini-1.5, and Claude-3.5, we observed an ASR of at least 95%
on the AdvBench dataset, which represents the current state-of-the-art. This
study underscores the urgent need to reassess the use of generative models in
critical applications to mitigate potential adverse societal impacts.
