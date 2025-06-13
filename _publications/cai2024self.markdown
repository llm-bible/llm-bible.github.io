---
layout: publication
title: 'Self-control Of LLM Behaviors By Compressing Suffix Gradient Into Prefix Controller'
authors: Min Cai, Yuchen Zhang, Shichang Zhang, Fan Yin, Dan Zhang, Difan Zou, Yisong Yue, Ziniu Hu
conference: "Arxiv"
year: 2024
bibkey: cai2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.02721'}
tags: ['Prompting', 'Efficiency and Optimization']
---
We propose SelfControl, an inference-time model control method utilizing
gradients to control the behavior of large language models (LLMs) without
explicit human annotations. Given a desired behavior expressed in a natural
language suffix string concatenated to the input prompt, SelfControl computes
gradients of the LLM's self-evaluation of the suffix with respect to its latent
representations. The gradients are used to directly control the auto-regressive
generation process towards desired behaviors, which eliminates human
supervision, achieves precise and transparent control, and offers on-the-fly
adaptability. To further enhance efficiency, we introduce SelfControl_\{Prefix\},
a compact module that encapsulates the learned representations from gradients
into a SelfControl_\{Prefix\}, facilitating efficient inference-time control with
no latency compared to the original model and allowing control for multiple
behaviors simultaneously. Our experiments demonstrate SelfControl's efficacy
across multiple domains, where it improves over SOTA for 8.3% in
detoxification, 3.1% in truthfulness enhancement, 4%~10% in controlling on
emotion tones, and 48.2% in privacy protection, i.e., completely remove privacy
leakage issue. Additionally, we demonstrate that SelfControl can be used for
data synthesis and to improve reasoning abilities.
