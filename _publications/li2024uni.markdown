---
layout: publication
title: Uni-MoE Scaling Unified Multimodal LLMs with Mixture of Experts
authors: Li Yunxin, Jiang Shenyuan, Hu Baotian, Wang Longyue, Zhong Wanqi, Luo Wenhan, Ma Lin, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: li2024uni
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11273"}
  - {name: "Code", url: "https://github.com/HITsz-TMG/UMOE-Scaling-Unified-Multimodal-LLMs"}
tags: ['ARXIV', 'Fine Tuning', 'Has Code', 'LLM', 'Multimodal Models', 'Tools']
---
Recent advancements in Multimodal Large Language Models (MLLMs) underscore the significance of scalable models and data to boost performance yet this often incurs substantial computational costs. Although the Mixture of Experts (MoE) architecture has been employed to efficiently scale large language and image-text models these efforts typically involve fewer experts and limited modalities. To address this our work presents the pioneering attempt to develop a unified MLLM with the MoE architecture named Uni-MoE that can handle a wide array of modalities. Specifically it features modality-specific encoders with connectors for a unified multimodal representation. We also implement a sparse MoE architecture within the LLMs to enable efficient training and inference through modality-level data parallelism and expert-level model parallelism. To enhance the multi-expert collaboration and generalization we present a progressive training strategy 1) Cross-modality alignment using various connectors with different cross-modality data 2) Training modality-specific experts with cross-modality instruction data to activate experts preferences and 3) Tuning the Uni-MoE framework utilizing Low-Rank Adaptation (LoRA) on mixed multimodal instruction data. We evaluate the instruction-tuned Uni-MoE on a comprehensive set of multimodal datasets. The extensive experimental results demonstrate Uni-MoEs principal advantage of significantly reducing performance bias in handling mixed multimodal datasets alongside improved multi-expert collaboration and generalization. Our findings highlight the substantial potential of MoE frameworks in advancing MLLMs and the code is available at https://github.com/HITsz-TMG/UMOE-Scaling-Unified-Multimodal-LLMs.
