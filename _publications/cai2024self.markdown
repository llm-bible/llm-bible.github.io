---
layout: publication
title: 'Self-control Of LLM Behaviors By Compressing Suffix Gradient Into Prefix Controller'
authors: Cai Min, Zhang Yuchen, Zhang Shichang, Yin Fan, Zou Difan, Yue Yisong, Hu Ziniu
conference: "Arxiv"
year: 2024
bibkey: cai2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02721"}
tags: ['Efficiency And Optimization', 'Pretraining Methods']
---
"We propose Self-Control, a novel method utilizing suffix gradients to control the behavior of large language models (LLMs) without explicit human annotations. Given a guideline expressed in suffix string and the model's self-assessment of adherence, Self-Control computes the gradient of this self-judgment concerning the model's hidden states, directly influencing the auto-regressive generation process towards desired behaviors. To enhance efficiency, we introduce Self-Control\_\{prefix\}, a compact module that encapsulates the learned representations from suffix gradients into a Prefix Controller, facilitating inference-time control for various LLM behaviors. Our experiments demonstrate Self-Control's efficacy across multiple domains, including emotional modulation, ensuring harmlessness, and enhancing complex reasoning. Especially, Self-Control\_\{prefix\} enables a plug-and-play control and jointly controls multiple attributes, improving model outputs without altering model parameters or increasing inference-time costs."
