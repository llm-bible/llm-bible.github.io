---
layout: publication
title: Specexec Massively Parallel Speculative Decoding For Interactive LLM Inference On Consumer Devices
authors: Svirschevski Ruslan, May Avner, Chen Zhuoming, Chen Beidi, Jia Zhihao, Ryabinin Max
conference: "Arxiv"
year: 2024
bibkey: svirschevski2024massively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02532"}
tags: ['Efficiency And Optimization', 'Quantization', 'Reinforcement Learning']
---
As large language models gain widespread adoption running them efficiently becomes crucial. Recent works on LLM inference use speculative decoding to achieve extreme speedups. However most of these works implicitly design their algorithms for high45;end datacenter hardware. In this work we ask the opposite question how fast can we run LLMs on consumer machines Consumer GPUs can no longer fit the largest available models (50B+ parameters) and must offload them to RAM or SSD. When running with offloaded parameters the inference engine can process batches of hundreds or thousands of tokens at the same time as just one token making it a natural fit for speculative decoding. We propose SpecExec (Speculative Execution) a simple parallel decoding method that can generate up to 20 tokens per target model iteration for popular LLM families. It utilizes the high spikiness of the token probabilities distribution in modern LLMs and a high degree of alignment between model output probabilities. SpecExec takes the most probable tokens continuation from the draft model to build a cache tree for the target model which then gets validated in a single pass. Using SpecExec we demonstrate inference of 50B+ parameter LLMs on consumer GPUs with RAM offloading at 445;6 tokens per second with 445;bit quantization or 245;3 tokens per second with 1645;bit weights.
