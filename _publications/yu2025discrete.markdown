---
layout: publication
title: 'Dimple: Discrete Diffusion Multimodal Large Language Model With Parallel Decoding'
authors: Runpeng Yu, Xinyin Ma, Xinchao Wang
conference: "Arxiv"
year: 2025
bibkey: yu2025discrete
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16990"}
  - {name: "Code", url: "https://github.com/yu-rp/Dimple"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Language Modeling', 'Merging', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Has Code', 'Prompting']
---
In this work, we propose Dimple, the first Discrete Diffusion Multimodal Large Language Model (DMLLM). We observe that training with a purely discrete diffusion approach leads to significant training instability, suboptimal performance, and severe length bias issues. To address these challenges, we design a novel training paradigm that combines an initial autoregressive phase with a subsequent diffusion phase. This approach yields the Dimple-7B model, trained on the same dataset and using a similar training pipeline as LLaVA-NEXT. Dimple-7B ultimately surpasses LLaVA-NEXT in performance by 3.9%, demonstrating that DMLLM can achieve performance comparable to that of autoregressive models. To improve inference efficiency, we propose a decoding strategy termed confident decoding, which dynamically adjusts the number of tokens generated at each step, significantly reducing the number of generation iterations. In autoregressive models, the number of forward iterations during generation equals the response length. With confident decoding, however, the number of iterations needed by Dimple is even only \\(\frac\{\text\{response length\}\}\{3\}\\). We also re-implement the prefilling technique in autoregressive models and demonstrate that it does not significantly impact performance on most benchmark evaluations, while offering a speedup of 1.5x to 7x. Additionally, we explore Dimple's capability to precisely control its response using structure priors. These priors enable structured responses in a manner distinct from instruction-based or chain-of-thought prompting, and allow fine-grained control over response format and length, which is difficult to achieve in autoregressive models. Overall, this work validates the feasibility and advantages of DMLLM and enhances its inference efficiency and controllability. Code and models are available at https://github.com/yu-rp/Dimple.
