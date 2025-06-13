---
layout: publication
title: 'Joint Fine-tuning And Conversion Of Pretrained Speech And Language Models Towards Linear Complexity'
authors: Mutian He, Philip N. Garner
conference: "Arxiv"
year: 2024
bibkey: he2024joint
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.06846'}
tags: ['Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Architectures such as Linformer and Mamba have recently emerged as
competitive linear time replacements for transformers. However, corresponding
large pretrained models are often unavailable, especially in non-text domains.
To remedy this, we present a Cross-Architecture Layerwise Distillation (CALD)
approach that jointly converts a transformer model to a linear time substitute
and fine-tunes it to a target task. We also compare several means to guide the
fine-tuning to optimally retain the desired inference capability from the
original model. The methods differ in their use of the target model and the
trajectory of the parameters. In a series of empirical studies on language
processing, language modeling, and speech processing, we show that CALD can
effectively recover the result of the original model, and that the guiding
strategy contributes to the result. Some reasons for the variation are
suggested.
