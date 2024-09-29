---
layout: publication
title: Self45;control Of LLM Behaviors By Compressing Suffix Gradient Into Prefix Controller
authors: Cai Min, Zhang Yuchen, Zhang Shichang, Yin Fan, Zou Difan, Yue Yisong, Hu Ziniu
conference: "Arxiv"
year: 2024
bibkey: cai2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02721"}
tags: ['Efficiency And Optimization', 'Pretraining Methods']
---
We propose Self45;Control a novel method utilizing suffix gradients to control the behavior of large language models (LLMs) without explicit human annotations. Given a guideline expressed in suffix string and the models self45;assessment of adherence Self45;Control computes the gradient of this self45;judgment concerning the models hidden states directly influencing the auto45;regressive generation process towards desired behaviors. To enhance efficiency we introduce Self45;Control95;123;prefix125; a compact module that encapsulates the learned representations from suffix gradients into a Prefix Controller facilitating inference45;time control for various LLM behaviors. Our experiments demonstrate Self45;Controls efficacy across multiple domains including emotional modulation ensuring harmlessness and enhancing complex reasoning. Especially Self45;Control95;123;prefix125; enables a plug45;and45;play control and jointly controls multiple attributes improving model outputs without altering model parameters or increasing inference45;time costs.
