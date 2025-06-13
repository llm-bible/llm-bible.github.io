---
layout: publication
title: 'In-context Lora For Diffusion Transformers'
authors: Lianghua Huang, Wei Wang, Zhi-fan Wu, Yupeng Shi, Huanzhang Dou, Chen Liang, Yutong Feng, Yu Liu, Jingren Zhou
conference: "Arxiv"
year: 2024
bibkey: huang2024lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23775"}
  - {name: "Code", url: "https://github.com/ali-vilab/In-Context-LoRA"}
tags: ['Arxiv', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Language Modeling', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Prompting', 'Applications', 'Attention Mechanism']
---
Recent research arXiv:2410.15027 has explored the use of diffusion
transformers (DiTs) for task-agnostic image generation by simply concatenating
attention tokens across images. However, despite substantial computational
resources, the fidelity of the generated images remains suboptimal. In this
study, we reevaluate and streamline this framework by hypothesizing that
text-to-image DiTs inherently possess in-context generation capabilities,
requiring only minimal tuning to activate them. Through diverse task
experiments, we qualitatively demonstrate that existing text-to-image DiTs can
effectively perform in-context generation without any tuning. Building on this
insight, we propose a remarkably simple pipeline to leverage the in-context
abilities of DiTs: (1) concatenate images instead of tokens, (2) perform joint
captioning of multiple images, and (3) apply task-specific LoRA tuning using
small datasets (e.g., 20~100 samples) instead of full-parameter tuning with
large datasets. We name our models In-Context LoRA (IC-LoRA). This approach
requires no modifications to the original DiT models, only changes to the
training data. Remarkably, our pipeline generates high-fidelity image sets that
better adhere to prompts. While task-specific in terms of tuning data, our
framework remains task-agnostic in architecture and pipeline, offering a
powerful tool for the community and providing valuable insights for further
research on product-level task-agnostic generation systems. We release our
code, data, and models at https://github.com/ali-vilab/In-Context-LoRA
