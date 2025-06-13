---
layout: publication
title: 'Logra-med: Long Context Multi-graph Alignment For Medical Vision-language Model'
authors: Duy M. H. Nguyen, Nghiem T. Diep, Trung Q. Nguyen, Hoang-bao Le, Tai Nguyen, Tien Nguyen, Trungtin Nguyen, Nhat Ho, Pengtao Xie, Roger Wattenhofer, James Zhou, Daniel Sonntag, Mathias Niepert
conference: "Arxiv"
year: 2024
bibkey: nguyen2024logra
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02615'}
tags: ['RAG', 'GPT', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
State-of-the-art medical multi-modal large language models (med-MLLM), like
LLaVA-Med or BioMedGPT, leverage instruction-following data in pre-training.
However, those models primarily focus on scaling the model size and data volume
to boost performance while mainly relying on the autoregressive learning
objectives. Surprisingly, we reveal that such learning schemes might result in
a weak alignment between vision and language modalities, making these models
highly reliant on extensive pre-training datasets - a significant challenge in
medical domains due to the expensive and time-consuming nature of curating
high-quality instruction-following instances. We address this with LoGra-Med, a
new multi-graph alignment algorithm that enforces triplet correlations across
image modalities, conversation-based descriptions, and extended captions. This
helps the model capture contextual meaning, handle linguistic variability, and
build cross-modal associations between visuals and text. To scale our approach,
we designed an efficient end-to-end learning scheme using black-box gradient
estimation, enabling faster LLaMa 7B training. Our results show LoGra-Med
matches LLAVA-Med performance on 600K image-text pairs for Medical VQA and
significantly outperforms it when trained on 10% of the data. For example, on
VQA-RAD, we exceed LLAVA-Med by 20.13% and nearly match the 100% pre-training
score (72.52% vs. 72.64%). We also surpass SOTA methods like BiomedGPT on
visual chatbots and RadFM on zero-shot image classification with VQA,
highlighting the effectiveness of multi-graph alignment.
