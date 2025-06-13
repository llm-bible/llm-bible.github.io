---
layout: publication
title: 'Introducing Visual Perception Token Into Multimodal Large Language Model'
authors: Runpeng Yu, Xinyin Ma, Xinchao Wang
conference: "Arxiv"
year: 2025
bibkey: yu2025introducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17425'}
  - {name: "Code", url: 'https://github.com/yu-rp/VisualPerceptionToken'}
tags: ['RAG', 'Has Code', 'Multimodal Models']
---
To utilize visual information, Multimodal Large Language Model (MLLM) relies
on the perception process of its vision encoder. The completeness and accuracy
of visual perception significantly influence the precision of spatial
reasoning, fine-grained understanding, and other tasks. However, MLLM still
lacks the autonomous capability to control its own visual perception processes,
for example, selectively reviewing specific regions of an image or focusing on
information related to specific object categories. In this work, we propose the
concept of Visual Perception Token, aiming to empower MLLM with a mechanism to
control its visual perception processes. We design two types of Visual
Perception Tokens, termed the Region Selection Token and the Vision Re-Encoding
Token. MLLMs autonomously generate these tokens, just as they generate text,
and use them to trigger additional visual perception actions. The Region
Selection Token explicitly identifies specific regions in an image that require
further perception, while the Vision Re-Encoding Token uses its hidden states
as control signals to guide additional visual perception processes. Extensive
experiments demonstrate the advantages of these tokens in handling spatial
reasoning, improving fine-grained understanding, and other tasks. On average,
the introduction of Visual Perception Tokens improves the performance of a 2B
model by 23.6%, increasing its score from 0.572 to 0.708, and even outperforms
a 7B parameter model by 13.4% (from 0.624). Please check out our repo
https://github.com/yu-rp/VisualPerceptionToken
