---
layout: publication
title: 'Enhancing Instruction-following Capability Of Visual-language Models By Reducing Image Redundancy'
authors: Te Yang, Jian Jia, Xiangyu Zhu, Weisong Zhao, Bo Wang, Yanhua Cheng, Yan Li, Shengyuan Liu, Quan Chen, Peng Jiang, Kun Gai, Zhen Lei
conference: "Arxiv"
year: 2024
bibkey: yang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15453"}
tags: ['Attention Mechanism', 'Multimodal Models', 'Model Architecture', 'Merging']
---
Large Language Models (LLMs) have strong instruction-following capability to
interpret and execute tasks as directed by human commands. Multimodal Large
Language Models (MLLMs) have inferior instruction-following ability compared to
LLMs. However, there is a significant gap in the instruction-following
capabilities between the MLLMs and LLMs. In this study, we conduct a pilot
experiment, which demonstrates that spatially down-sampling visual tokens
significantly enhances the instruction-following capability of MLLMs. This is
attributed to the substantial redundancy in visual modality. However, this
intuitive method severely impairs the MLLM's multimodal understanding
capability. In this paper, we propose Visual-Modality Token Compression (VMTC)
and Cross-Modality Attention Inhibition (CMAI) strategies to alleviate this gap
between MLLMs and LLMs by inhibiting the influence of irrelevant visual tokens
during content generation, increasing the instruction-following ability of the
MLLMs while retaining their multimodal understanding capacity. In VMTC module,
the primary tokens are retained and the redundant tokens are condensed by token
clustering and merging. In CMAI process, we aggregate text-to-image attentions
by text-to-text attentions to obtain a text-to-image focus score. Attention
inhibition is performed on the text-image token pairs with low scores. Our
comprehensive experiments over instruction-following capabilities and VQA-V2,
GQA, TextVQA, MME and MMBench five benchmarks, demonstrate that proposed
strategy significantly enhances the instruction following capability of MLLMs
while preserving the ability to understand and process multimodal inputs.
