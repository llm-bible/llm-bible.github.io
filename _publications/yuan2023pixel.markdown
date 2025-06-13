---
layout: publication
title: 'Osprey: Pixel Understanding With Visual Instruction Tuning'
authors: Yuqian Yuan, Wentong Li, Jian Liu, Dongqi Tang, Xinjie Luo, Chi Qin, Lei Zhang, Jianke Zhu
conference: "Arxiv"
year: 2023
bibkey: yuan2023pixel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10032"}
  - {name: "Code", url: "https://github.com/CircleRadon/Osprey"}
tags: ['Multimodal Models', 'Has Code']
---
Multimodal large language models (MLLMs) have recently achieved impressive
general-purpose vision-language capabilities through visual instruction tuning.
However, current MLLMs primarily focus on image-level or box-level
understanding, falling short in achieving fine-grained vision-language
alignment at pixel level. Besides, the lack of mask-based instruction data
limits their advancements. In this paper, we propose Osprey, a mask-text
instruction tuning approach, to extend MLLMs by incorporating fine-grained mask
regions into language instruction, aiming at achieving pixel-wise visual
understanding. To achieve this goal, we first meticulously curate a mask-based
region-text dataset with 724K samples, and then design a vision-language model
by injecting pixel-level representation into LLM. Specifically, Osprey adopts a
convolutional CLIP backbone as the vision encoder and employs a mask-aware
visual extractor to extract precise visual mask features from high resolution
input. Experimental results demonstrate Osprey's superiority in various region
understanding tasks, showcasing its new capability for pixel-level instruction
tuning. In particular, Osprey can be integrated with Segment Anything Model
(SAM) seamlessly to obtain multi-granularity semantics. The source code,
dataset and demo can be found at https://github.com/CircleRadon/Osprey.
