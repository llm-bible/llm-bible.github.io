---
layout: publication
title: Mobilequant\: Mobile-friendly Quantization For On-device Language Models
authors: Tan Fuwen, Lee Royson, Dudziak Łukasz, Hu Shell Xu, Bhattacharya Sourav, Hospedales Timothy, Tzimiropoulos Georgios, Martinez Brais
conference: "Arxiv"
year: 2024
bibkey: tan2024mobile
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13933"}
tags: ['Applications', 'Efficiency And Optimization', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have revolutionized language processing delivering outstanding results across multiple applications. However deploying LLMs on edge devices poses several challenges with respect to memory energy and compute costs limiting their widespread use in devices such as mobile phones. A promising solution is to reduce the number of bits used to represent weights and activations. While existing works have found partial success at quantizing LLMs to lower bitwidths e.g. 4-bit weights quantizing activations beyond 16 bits often leads to large computational overheads due to poor on-device quantization support or a considerable accuracy drop. Yet 8-bit activations are very attractive for on-device deployment as they would enable LLMs to fully exploit mobile-friendly hardware e.g. Neural Processing Units (NPUs). In this work we make a first attempt to facilitate the on-device deployment of LLMs using integer-only quantization. We first investigate the limitations of existing quantization methods for on-device deployment with a special focus on activation quantization. We then address these limitations by introducing a simple post-training quantization method named MobileQuant that extends previous weight equivalent transformation works by jointly optimizing the weight transformation and activation range parameters in an end-to-end manner. MobileQuant demonstrates superior capabilities over existing methods by 1) achieving near-lossless quantization on a wide range of LLM benchmarks 2) reducing latency and energy consumption by 2037;-5037; compared to current on-device quantization strategies 3) requiring limited compute budget 4) being compatible with mobile-friendly compute units e.g. NPU.
