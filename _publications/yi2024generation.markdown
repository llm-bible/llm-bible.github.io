---
layout: publication
title: Generation Meets Verification&#58; Accelerating Large Language Model Inference With Smart Parallel Auto-correct Decoding
authors: Yi Hanling, Lin Feng, Li Hongbin, Ning Peiyang, Yu Xiaotian, Xiao Rong
conference: "Arxiv"
year: 2024
bibkey: yi2024generation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11809"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Pretraining Methods', 'Training Techniques']
---
This research aims to accelerate the inference speed of large language models (LLMs) with billions of parameters. We propose (textbfS)mart (textbfP)arallel (textbfA)uto-(textbfC)orrect d(textbfE)coding (SPACE) an innovative approach designed for achieving lossless acceleration of LLMs. By integrating semi-autoregressive inference and speculative decoding capabilities SPACE uniquely enables autoregressive LLMs to parallelize token generation and verification. This is realized through a specialized semi-autoregressive supervised fine-tuning process that equips existing LLMs with the ability to simultaneously predict multiple tokens. Additionally an auto-correct decoding algorithm facilitates the simultaneous generation and verification of token sequences within a single model invocation. Through extensive experiments on a range of LLMs SPACE has demonstrated inference speedup ranging from 2.7x-4.0x on HumanEval-X while maintaining output quality.
