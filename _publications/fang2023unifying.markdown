---
layout: publication
title: 'Instructseq: Unifying Vision Tasks With Instruction-conditioned Multi-modal Sequence Generation'
authors: Fang Rongyao, Yan Shilin, Huang Zhaoyang, Zhou Jingqiu, Tian Hao, Dai Jifeng, Li Hongsheng
conference: "Arxiv"
year: 2023
bibkey: fang2023unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18835"}
  - {name: "Code", url: "https://github.com/rongyaofang/InstructSeq"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
'Empowering models to dynamically accomplish tasks specified through natural language instructions represents a promising path toward more capable and general artificial intelligence. In this work, we introduce InstructSeq, an instruction-conditioned multi-modal modeling framework that unifies diverse vision tasks through flexible natural language control and handling of both visual and textual data. InstructSeq employs a multimodal transformer architecture encompassing visual, language, and sequential modeling. We utilize a visual encoder to extract image features and a text encoder to encode instructions. An autoregressive transformer fuses the representations and generates sequential task outputs. By training with LLM-generated natural language instructions, InstructSeq acquires a strong comprehension of free-form instructions for specifying visual tasks. This provides an intuitive interface for directing capabilities using flexible natural instructions. Without any task-specific tuning, InstructSeq achieves compelling performance on semantic segmentation, referring expression segmentation/comprehension, and image captioning. The flexible control and multi-task unification empower the model with more human-like versatility and generalizability for computer vision. The code will be released soon at https://github.com/rongyaofang/InstructSeq.'
