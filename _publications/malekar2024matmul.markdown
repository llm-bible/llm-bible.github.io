---
layout: publication
title: Matmul or No Matmul in the Era of 1-bit LLMs
authors: Malekar Jinendra, Elbtity Mohammed E., Zand Ramtin
conference: "Arxiv"
year: 2024
bibkey: malekar2024matmul
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11939"}
tags: ['Model Architecture', 'Quantization', 'LLM', 'Arxiv']
---
The advent of 1-bit large language models (LLMs) has attracted considerable attention and opened up new research opportunities. However 1-bit LLMs only improve a fraction of models by applying extreme quantization to the projection layers while leaving attention heads unchanged. Therefore to avoid fundamentally wrong choices of goals in future research it is crucial to understand the actual improvements in computation and memory usage that 1-bit LLMs can deliver. In this work we present an adaptation of Amdahls Law tailored for the 1-bit LLM context which illustrates how partial improvements in 1-bit LLMs impact overall model performance. Through extensive experiments we uncover key nuances across different model architectures and hardware configurations offering a roadmap for future research in the era of 1-bit LLMs.
