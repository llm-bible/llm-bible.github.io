---
layout: publication
title: 'Exploring Implicit Visual Misunderstandings In Multimodal Large Language Models Through Attention Analysis'
authors: Pengfei Wang, Guohai Xu, Weinong Wang, Junjie Yang, Jie Lou, Yunhua Xue
conference: "Arxiv"
year: 2025
bibkey: wang2025exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10541'}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent advancements have enhanced the capability of Multimodal Large Language Models (MLLMs) to comprehend multi-image information. However, existing benchmarks primarily evaluate answer correctness, overlooking whether models genuinely comprehend the visual input. To address this, we define implicit visual misunderstanding (IVM), where MLLMs provide correct answers without fully comprehending the visual input. Through our analysis, we decouple the visual and textual modalities within the causal attention module, revealing that attention distribution increasingly converges on the image associated with the correct answer as the network layers deepen. This insight leads to the introduction of a scale-agnostic metric, \textit\{attention accuracy\}, and a novel benchmark for quantifying IVMs. Attention accuracy directly evaluates the model's visual understanding via internal mechanisms, remaining robust to positional biases for more reliable assessments. Furthermore, we extend our approach to finer granularities and demonstrate its effectiveness in unimodal scenarios, underscoring its versatility and generalizability.
