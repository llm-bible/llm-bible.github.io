---
layout: publication
title: 'VAR-CLIP: Text-to-image Generator With Visual Auto-regressive Modeling'
authors: Qian Zhang, Xiangzi Dai, Ninghua Yang, Xiang An, Ziyong Feng, Xingyu Ren
conference: "Arxiv"
year: 2024
bibkey: zhang2024var
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01181"}
  - {name: "Code", url: "https://github.com/daixiangzi/VAR-CLIP"}
tags: ['Transformer', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
VAR is a new generation paradigm that employs 'next-scale prediction' as
opposed to 'next-token prediction'. This innovative transformation enables
auto-regressive (AR) transformers to rapidly learn visual distributions and
achieve robust generalization. However, the original VAR model is constrained
to class-conditioned synthesis, relying solely on textual captions for
guidance. In this paper, we introduce VAR-CLIP, a novel text-to-image model
that integrates Visual Auto-Regressive techniques with the capabilities of
CLIP. The VAR-CLIP framework encodes captions into text embeddings, which are
then utilized as textual conditions for image generation. To facilitate
training on extensive datasets, such as ImageNet, we have constructed a
substantial image-text dataset leveraging BLIP2. Furthermore, we delve into the
significance of word positioning within CLIP for the purpose of caption
guidance. Extensive experiments confirm VAR-CLIP's proficiency in generating
fantasy images with high fidelity, textual congruence, and aesthetic
excellence. Our project page are https://github.com/daixiangzi/VAR-CLIP
