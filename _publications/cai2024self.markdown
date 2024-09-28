---
layout: publication
title: Self-Control of LLM Behaviors by Compressing Suffix Gradient into Prefix Controller
authors: Cai Min, Zhang Yuchen, Zhang Shichang, Yin Fan, Zou Difan, Yue Yisong, Hu Ziniu
conference: "Arxiv"
year: 2024
bibkey: cai2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02721"}
tags: ['ARXIV', 'Efficiency And Optimization', 'LLM']
---
We propose Self-Control a novel method utilizing suffix gradients to control the behavior of large language models (LLMs) without explicit human annotations. Given a guideline expressed in suffix string and the models self-assessment of adherence Self-Control computes the gradient of this self-judgment concerning the models hidden states directly influencing the auto-regressive generation process towards desired behaviors. To enhance efficiency we introduce Self-Control_prefix a compact module that encapsulates the learned representations from suffix gradients into a Prefix Controller facilitating inference-time control for various LLM behaviors. Our experiments demonstrate Self-Controls efficacy across multiple domains including emotional modulation ensuring harmlessness and enhancing complex reasoning. Especially Self-Control_prefix enables a plug-and-play control and jointly controls multiple attributes improving model outputs without altering model parameters or increasing inference-time costs.
