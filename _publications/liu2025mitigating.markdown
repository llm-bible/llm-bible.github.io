---
layout: publication
title: 'Mitigating Heterogeneous Token Overfitting In LLM Knowledge Editing'
authors: Tianci Liu, Ruirui Li, Zihan Dong, Hui Liu, Xianfeng Tang, Qingyu Yin, Linjun Zhang, Haoyu Wang, Jing Gao
conference: "Arxiv"
year: 2025
bibkey: liu2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00602"}
tags: ['Reinforcement Learning']
---
Large language models (LLMs) have achieved remarkable performance on various natural language tasks. However, they are trained on static corpora and their knowledge can become outdated quickly in the fast-changing world. This motivates the development of knowledge editing (KE) to update specific knowledge in LLMs without changing unrelated others or compromising their pre-trained capabilities. Previous efforts sought to update a small amount of parameters of a LLM and proved effective for making selective updates. Nonetheless, the edited LLM often exhibits degraded ability to reason about the new knowledge. In this work, we identify a key issue: heterogeneous token overfitting (HTO), where the LLM overfits different tokens in the provided knowledge at varying rates. To tackle this, we propose OVERTONE, a token-level smoothing method that mitigates HTO by adaptively refining the target distribution. Theoretically, OVERTONE offers better parameter updates with negligible computation overhead. It also induces an implicit DPO but does not require preference data pairs. Extensive experiments across four editing methods, two LLMs, and diverse scenarios demonstrate the effectiveness and versatility of our method.
