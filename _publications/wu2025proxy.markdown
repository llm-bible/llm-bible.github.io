---
layout: publication
title: 'Proxy-tuning: Tailoring Multimodal Autoregressive Models For Subject-driven Image Generation'
authors: Yi Wu, Lingting Zhu, Lei Liu, Wandi Qiao, Ziqiang Li, Lequan Yu, Bin Li
conference: "Arxiv"
year: 2025
bibkey: wu2025proxy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10125"}
tags: ['Transformer', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Multimodal autoregressive (AR) models, based on next-token prediction and
transformer architecture, have demonstrated remarkable capabilities in various
multimodal tasks including text-to-image (T2I) generation. Despite their strong
performance in general T2I tasks, our research reveals that these models
initially struggle with subject-driven image generation compared to dominant
diffusion models. To address this limitation, we introduce Proxy-Tuning,
leveraging diffusion models to enhance AR models' capabilities in
subject-specific image generation. Our method reveals a striking weak-to-strong
phenomenon: fine-tuned AR models consistently outperform their diffusion model
supervisors in both subject fidelity and prompt adherence. We analyze this
performance shift and identify scenarios where AR models excel, particularly in
multi-subject compositions and contextual understanding. This work not only
demonstrates impressive results in subject-driven AR image generation, but also
unveils the potential of weak-to-strong generalization in the image generation
domain, contributing to a deeper understanding of different architectures'
strengths and limitations.
