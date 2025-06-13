---
layout: publication
title: 'Cross-image Contrastive Decoding: Precise, Lossless Suppression Of Language Priors In Large Vision-language Models'
authors: Jianfei Zhao, Feng Zhang, Xin Sun, Chong Feng
conference: "Arxiv"
year: 2025
bibkey: zhao2025cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10634"}
tags: ['Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Language priors are a major cause of hallucinations in Large Vision-Language Models (LVLMs), often leading to text that is linguistically plausible but visually inconsistent. Recent work explores contrastive decoding as a training-free solution, but these methods typically construct negative contexts from the original image, resulting in visual information loss and distorted distribution. Motivated by the observation that language priors stem from the LLM backbone and remain consistent across images, we propose Cross-Images Contrastive Decoding (CICD), a simple yet effective training-free method that uses different images to construct negative contexts. We further analyze the cross-image behavior of language priors and introduce a distinction between essential priors (supporting fluency) and detrimental priors (causing hallucinations). By selectively preserving essential priors and suppressing detrimental ones, our method reduces hallucinations while maintaining coherent and fluent language generation. Experiments on 4 benchmarks and 6 LVLMs across three model families confirm the effectiveness and generalizability of CICD, especially in image captioning, where language priors are particularly pronounced. Code will be released once accepted.
