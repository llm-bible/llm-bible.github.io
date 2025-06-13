---
layout: publication
title: 'Visual Perturbation And Adaptive Hard Negative Contrastive Learning For Compositional Reasoning In Vision-language Models'
authors: Xin Huang, Ruibin Li, Tong Jia, Wei Zheng, Ya Wang
conference: "Arxiv"
year: 2025
bibkey: huang2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15576"}
  - {name: "Code", url: "https://github.com/nynu-BDAI/AHNPL"}
tags: ['Training Techniques', 'Multimodal Models', 'Has Code', 'Pretraining Methods']
---
Vision-Language Models (VLMs) are essential for multimodal tasks, especially compositional reasoning (CR) tasks, which require distinguishing fine-grained semantic differences between visual and textual embeddings. However, existing methods primarily fine-tune the model by generating text-based hard negative samples, neglecting the importance of image-based negative samples, which results in insufficient training of the visual encoder and ultimately impacts the overall performance of the model. Moreover, negative samples are typically treated uniformly, without considering their difficulty levels, and the alignment of positive samples is insufficient, which leads to challenges in aligning difficult sample pairs. To address these issues, we propose Adaptive Hard Negative Perturbation Learning (AHNPL). AHNPL translates text-based hard negatives into the visual domain to generate semantically disturbed image-based negatives for training the model, thereby enhancing its overall performance. AHNPL also introduces a contrastive learning approach using a multimodal hard negative loss to improve the model's discrimination of hard negatives within each modality and a dynamic margin loss that adjusts the contrastive margin according to sample difficulty to enhance the distinction of challenging sample pairs. Experiments on three public datasets demonstrate that our method effectively boosts VLMs' performance on complex CR tasks. The source code is available at https://github.com/nynu-BDAI/AHNPL.
