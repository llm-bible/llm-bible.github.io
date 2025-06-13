---
layout: publication
title: 'Image Editing As Programs With Diffusion Models'
authors: Yujia Hu, Songhua Liu, Zhenxiong Tan, Xingyi Yang, Xinchao Wang
conference: "Arxiv"
year: 2025
bibkey: hu2025image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04158"}
  - {name: "Code", url: "https://github.com/YujiaHu1109/IEAP"}
tags: ['Transformer', 'Agentic', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
While diffusion models have achieved remarkable success in text-to-image generation, they encounter significant challenges with instruction-driven image editing. Our research highlights a key challenge: these models particularly struggle with structurally inconsistent edits that involve substantial layout changes. To mitigate this gap, we introduce Image Editing As Programs (IEAP), a unified image editing framework built upon the Diffusion Transformer (DiT) architecture. At its core, IEAP approaches instructional editing through a reductionist lens, decomposing complex editing instructions into sequences of atomic operations. Each operation is implemented via a lightweight adapter sharing the same DiT backbone and is specialized for a specific type of edit. Programmed by a vision-language model (VLM)-based agent, these operations collaboratively support arbitrary and structurally inconsistent transformations. By modularizing and sequencing edits in this way, IEAP generalizes robustly across a wide range of editing tasks, from simple adjustments to substantial structural changes. Extensive experiments demonstrate that IEAP significantly outperforms state-of-the-art methods on standard benchmarks across various editing scenarios. In these evaluations, our framework delivers superior accuracy and semantic fidelity, particularly for complex, multi-step instructions. Codes are available at https://github.com/YujiaHu1109/IEAP.
