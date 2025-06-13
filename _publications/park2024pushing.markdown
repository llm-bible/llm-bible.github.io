---
layout: publication
title: 'Pushing The Envelope Of Low-bit LLM Via Dynamic Error Compensation'
authors: Yeonhong Park, Jake Hyun, Hojoon Kim, Jae W. Lee
conference: "Arxiv"
year: 2024
bibkey: park2024pushing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20185"}
tags: ['Efficiency and Optimization', 'Quantization', 'Reinforcement Learning']
---
Quantization of Large Language Models (LLMs) has recently gained popularity,
particularly for on-device settings with limited hardware resources. While
efficient, quantization inevitably degrades model quality, especially in
aggressive low-bit settings such as 3-bit and 4-bit precision. In this paper,
we propose QDEC, an inference scheme that improves the quality of low-bit LLMs
while preserving the key benefits of quantization: GPU memory savings and
inference latency reduction. QDEC stores the residual matrix -- the difference
between full-precision and quantized weights -- in CPU, and dynamically fetches
the residuals for only a small portion of the weights. This portion corresponds
to the salient channels, marked by activation outliers, with the fetched
residuals helping to correct quantization errors in these channels. Salient
channels are identified dynamically at each decoding step by analyzing the
input activations -- this allows for the adaptation to the dynamic nature of
activation distribution, and thus maximizes the effectiveness of error
compensation. We demonstrate the effectiveness of QDEC by augmenting
state-of-the-art quantization methods. For example, QDEC reduces the perplexity
of a 3-bit Llama-3-8B-Instruct model from 10.15 to 9.12 -- outperforming its
3.5-bit counterpart -- while adding less than 0.0003% to GPU memory usage and
incurring only a 1.7% inference slowdown on NVIDIA RTX 4050 Mobile GPU. The
code will be publicly available soon.
