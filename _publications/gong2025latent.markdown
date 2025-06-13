---
layout: publication
title: 'Latent Preference Coding: Aligning Large Language Models Via Discrete Latent Codes'
authors: Zhuocheng Gong, Jian Guan, Wei Wu, Huishuai Zhang, Dongyan Zhao
conference: "Arxiv"
year: 2025
bibkey: gong2025latent
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04993'}
tags: ['Reinforcement Learning', 'Security', 'Tools']
---
Large language models (LLMs) have achieved remarkable success, yet aligning
their generations with human preferences remains a critical challenge. Existing
approaches to preference modeling often rely on an explicit or implicit reward
function, overlooking the intricate and multifaceted nature of human
preferences that may encompass conflicting factors across diverse tasks and
populations. To address this limitation, we introduce Latent Preference Coding
(LPC), a novel framework that models the implicit factors as well as their
combinations behind holistic preferences using discrete latent codes. LPC
seamlessly integrates with various offline alignment algorithms, automatically
inferring the underlying factors and their importance from data without relying
on pre-defined reward functions and hand-crafted combination weights. Extensive
experiments on multiple benchmarks demonstrate that LPC consistently improves
upon three alignment algorithms (DPO, SimPO, and IPO) using three base models
(Mistral-7B, Llama3-8B, and Llama3-8B-Instruct). Furthermore, deeper analysis
reveals that the learned latent codes effectively capture the differences in
the distribution of human preferences and significantly enhance the robustness
of alignment against noise in data. By providing a unified representation for
the multifarious preference factors, LPC paves the way towards developing more
robust and versatile alignment techniques for the responsible deployment of
powerful LLMs.
