---
layout: publication
title: 'Ml-specqd: Multi-level Speculative Decoding With Quantized Drafts'
authors: Evangelos Georganas, Dhiraj Kalamkar, Alexander Kozlov, Alexander Heinecke
conference: "Arxiv"
year: 2025
bibkey: georganas2025ml
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13565'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Reinforcement Learning', 'Pre-Training']
---
Speculative decoding (SD) has emerged as a method to accelerate LLM inference
without sacrificing any accuracy over the 16-bit model inference. In a typical
SD setup, the idea is to use a full-precision, small, fast model as "draft" to
generate the next few tokens and use the "target" large model to verify the
draft-generated tokens. The efficacy of this method heavily relies on the
acceptance ratio of the draft-generated tokens and the relative token
throughput of the draft versus the target model. Nevertheless, an efficient SD
pipeline requires pre-training and aligning the draft model to the target
model, making it impractical for LLM inference in a plug-and-play fashion. In
this work, we propose using MXFP4 models as drafts in a plug-and-play fashion
since the MXFP4 Weight-Only-Quantization (WOQ) merely direct-casts the BF16
target model weights to MXFP4. In practice, our plug-and-play solution gives
speedups up to 2x over the BF16 baseline. Then we pursue an opportunity for
further acceleration: the MXFP4 draft token generation itself can be
accelerated via speculative decoding by using yet another smaller draft. We
call our method ML-SpecQD: Multi-Level Speculative Decoding with Quantized
Drafts since it recursively applies speculation for accelerating the
draft-token generation. Combining Multi-Level Speculative Decoding with MXFP4
Quantized Drafts we outperform state-of-the-art speculative decoding, yielding
speedups up to 2.72x over the BF16 baseline.
