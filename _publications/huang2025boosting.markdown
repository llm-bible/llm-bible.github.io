---
layout: publication
title: 'Ctrldiff: Boosting Large Diffusion Language Models With Dynamic Block Prediction And Controllable Generation'
authors: Chihan Huang, Hao Tang
conference: "Arxiv"
year: 2025
bibkey: huang2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14455"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Although autoregressive models have dominated language modeling in recent years, there has been a growing interest in exploring alternative paradigms to the conventional next-token prediction framework. Diffusion-based language models have emerged as a compelling alternative due to their powerful parallel generation capabilities and inherent editability. However, these models are often constrained by fixed-length generation. A promising direction is to combine the strengths of both paradigms, segmenting sequences into blocks, modeling autoregressive dependencies across blocks while leveraging discrete diffusion to estimate the conditional distribution within each block given the preceding context. Nevertheless, their practical application is often hindered by two key limitations: rigid fixed-length outputs and a lack of flexible control mechanisms. In this work, we address the critical limitations of fixed granularity and weak controllability in current large diffusion language models. We propose CtrlDiff, a dynamic and controllable semi-autoregressive framework that adaptively determines the size of each generation block based on local semantics using reinforcement learning. Furthermore, we introduce a classifier-guided control mechanism tailored to discrete diffusion, which significantly reduces computational overhead while facilitating efficient post-hoc conditioning without retraining. Extensive experiments demonstrate that CtrlDiff sets a new standard among hybrid diffusion models, narrows the performance gap to state-of-the-art autoregressive approaches, and enables effective conditional text generation across diverse tasks.
