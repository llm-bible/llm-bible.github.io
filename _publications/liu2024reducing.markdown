---
layout: publication
title: 'Reducing Hallucinations In Vision-language Models Via Latent Space Steering'
authors: Sheng Liu, Haotian Ye, Lei Xing, James Zou
conference: "Arxiv"
year: 2024
bibkey: liu2024reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15778'}
tags: ['Reinforcement Learning', 'Multimodal Models', 'Applications']
---
Hallucination poses a challenge to the deployment of large vision-language
models (LVLMs) in applications. Unlike in large language models (LLMs),
hallucination in LVLMs often arises from misalignments between visual inputs
and textual outputs. This paper investigates the underlying mechanisms of
hallucination, focusing on the unique structure of LVLMs that distinguishes
them from large language models (LLMs). We identify that hallucinations often
arise from the sensitivity of text decoders to vision inputs, a natural
phenomenon when image encoders and text decoders are pre-trained separately.
Inspired by this, we introduce Visual and Textual Intervention (VTI), a novel
technique designed to reduce hallucinations by steering latent space
representations during inference to enhance the stability of vision features.
As a task-agnostic test-time intervention, VTI can be easily applied to any
problem without additional cost. Extensive experiments demonstrate that it can
effectively reduce hallucinations and outperform baseline methods across
multiple metrics, highlighting the critical role of vision feature stability in
LVLMs.
