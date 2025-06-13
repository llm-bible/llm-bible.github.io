---
layout: publication
title: 'Cerberus: Efficient Inference With Adaptive Parallel Decoding And Sequential Knowledge Enhancement'
authors: Yuxuan Liu, Wenyuan Li, Laizhong Cui, Hailiang Yang
conference: "Arxiv"
year: 2024
bibkey: liu2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13344'}
tags: ['Efficiency and Optimization', 'Tools']
---
Large language models (LLMs) often face a bottleneck in inference speed due
to their reliance on auto-regressive decoding. Recently, parallel decoding has
shown significant promise in enhancing inference efficiency. However, we have
identified two key issues with existing parallel decoding frameworks: (1)
decoding heads fail to balance prediction accuracy and the parallelism of
execution, and (2) parallel decoding is not a universal solution, as it can
bring unnecessary overheads at some challenging decoding steps. To address
these issues, we propose Cerberus, an adaptive parallel decoding framework
introduces the gating mechanism to enable the LLMs to adaptively choose
appropriate decoding approaches at each decoding step, along with introducing a
new paradigm of decoding heads that introduce the sequential knowledge while
maintaining execution parallelism. The experiment results demonstrate that the
Cerberus can achieve up to 2.12x speed up compared to auto-regressive decoding,
and outperforms one of the leading parallel decoding frameworks, Medusa, with a
10% - 30% increase in acceleration and superior generation quality.
