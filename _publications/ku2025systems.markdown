---
layout: publication
title: 'Systems And Algorithms For Convolutional Multi-hybrid Language Models At Scale'
authors: Jerome Ku, Eric Nguyen, David W. Romero, Garyk Brixi, Brandon Yang, Anton Vorontsov, Ali Taghibakhshi, Amy X. Lu, Dave P. Burke, Greg Brockman, Stefano Massaroli, Christopher Ré, Patrick D. Hsu, Brian L. Hie, Stefano Ermon, Michael Poli
conference: "Arxiv"
year: 2025
bibkey: ku2025systems
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01868'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
We introduce convolutional multi-hybrid architectures, with a design grounded
on two simple observations. First, operators in hybrid models can be tailored
to token manipulation tasks such as in-context recall, multi-token recall, and
compression, with input-dependent convolutions and attention offering
complementary performance. Second, co-designing convolution operators and
hardware-aware algorithms enables efficiency gains in regimes where previous
alternative architectures struggle to surpass Transformers. At the 40 billion
parameter scale, we train end-to-end 1.2 to 2.9 times faster than optimized
Transformers, and 1.1 to 1.4 times faster than previous generation hybrids. On
H100 GPUs and model width 4096, individual operators in the proposed
multi-hybrid StripedHyena 2 architecture achieve two-fold throughput
improvement over linear attention and state-space models. Multi-hybrids excel
at sequence modeling over byte-tokenized data, as demonstrated by the Evo 2
line of models. We discuss the foundations that enable these results, including
architecture design, overlap-add blocked kernels for tensor cores, and
dedicated all-to-all and point-to-point context parallelism strategies.
