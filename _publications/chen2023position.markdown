---
layout: publication
title: 'Position-enhanced Visual Instruction Tuning For Multimodal Large Language Models'
authors: Chen Chi, Qin Ruoyu, Luo Fuwen, Mi Xiaoyue, Li Peng, Sun Maosong, Liu Yang
conference: "Arxiv"
year: 2023
bibkey: chen2023position
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13437"}
  - {name: "Code", url: "https://github.com/PVIT-official/PVIT"}
tags: ['Has Code', 'Multimodal Models']
---
Recently, Multimodal Large Language Models (MLLMs) that enable Large Language
Models (LLMs) to interpret images through visual instruction tuning have
achieved significant success. However, existing visual instruction tuning
methods only utilize image-language instruction data to align the language and
image modalities, lacking a more fine-grained cross-modal alignment. In this
paper, we propose Position-enhanced Visual Instruction Tuning (PVIT), which
extends the functionality of MLLMs by integrating an additional region-level
vision encoder. This integration promotes a more detailed comprehension of
images for the MLLM. In addition, to efficiently achieve a fine-grained
alignment between the vision modules and the LLM, we design multiple data
generation strategies to construct an image-region-language instruction
dataset. Finally, we present both quantitative experiments and qualitative
analysis that demonstrate the superiority of the proposed model. Code and data
will be released at https://github.com/PVIT-official/PVIT.
