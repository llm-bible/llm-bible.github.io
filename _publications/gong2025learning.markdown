---
layout: publication
title: 'Relationadapter: Learning And Transferring Visual Relation With Diffusion Transformers'
authors: Yan Gong, Yiren Song, Yicheng Li, Chenglin Li, Yin Zhang
conference: "Arxiv"
year: 2025
bibkey: gong2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02528'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Merging', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Inspired by the in-context learning mechanism of large language models (LLMs), a new paradigm of generalizable visual prompt-based image editing is emerging. Existing single-reference methods typically focus on style or appearance adjustments and struggle with non-rigid transformations. To address these limitations, we propose leveraging source-target image pairs to extract and transfer content-aware editing intent to novel query images. To this end, we introduce RelationAdapter, a lightweight module that enables Diffusion Transformer (DiT) based models to effectively capture and apply visual transformations from minimal examples. We also introduce Relation252K, a comprehensive dataset comprising 218 diverse editing tasks, to evaluate model generalization and adaptability in visual prompt-driven scenarios. Experiments on Relation252K show that RelationAdapter significantly improves the model's ability to understand and transfer editing intent, leading to notable gains in generation quality and overall editing performance.
