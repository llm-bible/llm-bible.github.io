---
layout: publication
title: 'Shapellm-omni: A Native Multimodal LLM For 3D Generation And Understanding'
authors: Junliang Ye, Zhengyi Wang, Ruowen Zhao, Shenghao Xie, Jun Zhu
conference: "Arxiv"
year: 2025
bibkey: ye2025shapellm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01853"}
  - {name: "Code", url: "https://github.com/JAMESYJL/ShapeLLM-Omni"}
tags: ['GPT', 'Model Architecture', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Recently, the powerful text-to-image capabilities of ChatGPT-4o have led to growing appreciation for native multimodal large language models. However, its multimodal capabilities remain confined to images and text. Yet beyond images, the ability to understand and generate 3D content is equally crucial. To address this gap, we propose ShapeLLM-Omni-a native 3D large language model capable of understanding and generating 3D assets and text in any sequence. First, we train a 3D vector-quantized variational autoencoder (VQVAE), which maps 3D objects into a discrete latent space to achieve efficient and accurate shape representation and reconstruction. Building upon the 3D-aware discrete tokens, we innovatively construct a large-scale continuous training dataset named 3D-Alpaca, encompassing generation, comprehension, and editing, thus providing rich resources for future research and training. Finally, by performing instruction-based training of the Qwen-2.5-vl-7B-Instruct model on the 3D-Alpaca dataset. Our work provides an effective attempt at extending multimodal models with basic 3D capabilities, which contributes to future research in 3D-native AI. Project page: https://github.com/JAMESYJL/ShapeLLM-Omni
