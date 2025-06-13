---
layout: publication
title: 'Instruction-aligned Visual Attention For Mitigating Hallucinations In Large Vision-language Models'
authors: Bin Li, Dehong Gao, Yeyuan Wang, Linbo Jin, Shanqing Yu, Xiaoyan Cai, Libin Yang
conference: "Arxiv"
year: 2025
bibkey: li2025instruction
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.18556'}
  - {name: "Code", url: 'https://github.com/Lee-lab558/IAVA'}
tags: ['Attention Mechanism', 'Has Code', 'Multimodal Models', 'Model Architecture']
---
Despite the significant success of Large Vision-Language models(LVLMs), these
models still suffer hallucinations when describing images, generating answers
that include non-existent objects. It is reported that these models tend to
over-focus on certain irrelevant image tokens that do not contain critical
information for answering the question and distort the output. To address this,
we propose an Instruction-Aligned Visual Attention(IAVA) approach, which
identifies irrelevant tokens by comparing changes in attention weights under
two different instructions. By applying contrastive decoding, we dynamically
adjust the logits generated from original image tokens and irrelevant image
tokens, reducing the model's over-attention to irrelevant information. The
experimental results demonstrate that IAVA consistently outperforms existing
decoding techniques on benchmarks such as MME, POPE, and TextVQA in mitigating
object hallucinations. Our IAVA approach is available online at
https://github.com/Lee-lab558/IAVA.
