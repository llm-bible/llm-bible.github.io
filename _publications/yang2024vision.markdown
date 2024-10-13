---
layout: publication
title: '3D Vision And Language Pretraining With Large-scale Synthetic Data'
authors: Yang Dejie, Xu Zhu, Mo Wentao, Chen Qingchao, Huang Siyuan, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: yang2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06084"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'TACL', 'Training Techniques', 'Transformer']
---
3D Vision-Language Pre-training (3D-VLP) aims to provide a pre-train model
which can bridge 3D scenes with natural language, which is an important
technique for embodied intelligence. However, current 3D-VLP datasets are
hindered by limited scene-level diversity and insufficient fine-grained
annotations (only 1.2K scenes and 280K textual annotations in ScanScribe),
primarily due to the labor-intensive of collecting and annotating 3D scenes. To
overcome these obstacles, we construct SynVL3D, a comprehensive synthetic
scene-text corpus with 10K indoor scenes and 1M descriptions at object, view,
and room levels, which has the advantages of diverse scene data, rich textual
descriptions, multi-grained 3D-text associations, and low collection cost.
Utilizing the rich annotations in SynVL3D, we pre-train a simple and unified
Transformer for aligning 3D and language with multi-grained pretraining tasks.
Moreover, we propose a synthetic-to-real domain adaptation in downstream task
fine-tuning process to address the domain shift. Through extensive experiments,
we verify the effectiveness of our model design by achieving state-of-the-art
performance on downstream tasks including visual grounding, dense captioning,
and question answering.
