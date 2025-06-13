---
layout: publication
title: 'Cross-self KV Cache Pruning For Efficient Vision-language Inference'
authors: Xiaohuan Pei, Tao Huang, Chang Xu
conference: "Arxiv"
year: 2024
bibkey: pei2024cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04652'}
  - {name: "Code", url: 'https://github.com/TerryPei/CSP'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Multimodal Models', 'Reinforcement Learning']
---
KV cache pruning has emerged as a promising technique for reducing memory and
computation costs in long-context auto-regressive generation. Existing methods
for vision-language models (VLMs) typically rely on self-attention scores from
large language models (LLMs) to identify and prune irrelevant tokens. However,
these approaches overlook the inherent distributional discrepancies between
modalities, often leading to inaccurate token importance estimation and the
over-pruning of critical visual tokens. To address this, we propose decomposing
attention scores into intra-modality attention (within the same modality) and
inter-modality attention (across modalities), enabling more precise KV cache
pruning by independently managing these distinct attention types. Additionally,
we introduce an n-softmax function to counteract distribution shifts caused by
pruning, preserving the original smoothness of attention scores and ensuring
stable performance. Our final training-free method,
\textbf\{C\}ross-\textbf\{S\}elf \textbf\{P\}runing (CSP), achieves competitive
performance compared to models with full KV caches while significantly
outperforming previous pruning methods. Extensive evaluations on MileBench, a
benchmark encompassing 29 multimodal datasets, demonstrate CSP's effectiveness,
achieving up to a 41% performance improvement on challenging tasks like
conversational embodied dialogue while reducing the KV cache budget by 13.6%.
The code is available at https://github.com/TerryPei/CSP
