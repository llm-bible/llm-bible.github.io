---
layout: publication
title: 'Bergeron: Combating Adversarial Attacks Through A Conscience-based Alignment Framework'
authors: Matthew Pisano, Peter Ly, Abraham Sanders, Bingsheng Yao, Dakuo Wang, Tomek Strzalkowski, Mei Si
conference: "Arxiv"
year: 2023
bibkey: pisano2023combating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.00029"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Research into AI alignment has grown considerably since the recent
introduction of increasingly capable Large Language Models (LLMs).
Unfortunately, modern methods of alignment still fail to fully prevent harmful
responses when models are deliberately attacked. Such vulnerabilities can lead
to LLMs being manipulated into generating hazardous content: from instructions
for creating dangerous materials to inciting violence or endorsing unethical
behaviors. To help mitigate this issue, we introduce Bergeron: a framework
designed to improve the robustness of LLMs against attacks without any
additional parameter fine-tuning. Bergeron is organized into two tiers; with a
secondary LLM acting as a guardian to the primary LLM. This framework better
safeguards the primary model against incoming attacks while monitoring its
output for any harmful content. Empirical analysis reviews that by using
Bergeron to complement models with existing alignment training, we can
significantly improve the robustness and safety of multiple, commonly used
commercial and open-source LLMs. Specifically, we found that models integrated
with Bergeron are, on average, nearly seven times more resistant to attacks
compared to models without such support.
