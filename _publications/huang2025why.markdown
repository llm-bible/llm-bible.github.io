---
layout: publication
title: 'Why Vision Language Models Struggle With Visual Arithmetic? Towards Enhanced Chart And Geometry Understanding'
authors: Kung-hsiang Huang, Can Qin, Haoyi Qiu, Philippe Laban, Shafiq Joty, Caiming Xiong, Chien-sheng Wu
conference: "Arxiv"
year: 2025
bibkey: huang2025why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11492"}
tags: ['Multimodal Models', 'Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Vision Language Models (VLMs) have achieved remarkable progress in multimodal tasks, yet they often struggle with visual arithmetic, seemingly simple capabilities like object counting or length comparison, which are essential for relevant complex tasks like chart understanding and geometric reasoning. In this work, we first investigate the root causes of this deficiency through a suite of probing tasks focusing on basic visual arithmetic. Our analysis reveals that while pre-trained vision encoders typically capture sufficient information, the text decoder often fails to decode it correctly for arithmetic reasoning. To address this, we propose CogAlign, a novel post-training strategy inspired by Piaget's theory of cognitive development. CogAlign trains VLMs to recognize invariant properties under visual transformations. We demonstrate that this approach significantly improves the performance of three diverse VLMs on our proposed probing tasks. Furthermore, CogAlign enhances performance by an average of 4.6% on CHOCOLATE and 2.9% on MATH-VISION, outperforming or matching supervised fine-tuning methods while requiring only 60% less training data. These results highlight the effectiveness and generalizability of CogAlign in improving fundamental visual arithmetic capabilities and their transfer to downstream tasks.
