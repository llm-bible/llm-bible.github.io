---
layout: publication
title: 'Unicorn: Text-only Data Synthesis For Vision Language Model Training'
authors: Xiaomin Yu, Pengxiang Ding, Wenjie Zhang, Siteng Huang, Songyang Gao, Chengwei Qin, Kejian Wu, Zhaoxin Fan, Ziyue Qiao, Donglin Wang
conference: "Arxiv"
year: 2025
bibkey: yu2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.22655'}
  - {name: "Code", url: 'https://github.com/Yu-xm/Unicorn.git'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Training vision-language models (VLMs) typically requires large-scale,
high-quality image-text pairs, but collecting or synthesizing such data is
costly. In contrast, text data is abundant and inexpensive, prompting the
question: can high-quality multimodal training data be synthesized purely from
text? To tackle this, we propose a cross-integrated three-stage multimodal data
synthesis framework, which generates two datasets: Unicorn-1.2M and
Unicorn-471K-Instruction. In Stage 1: Diverse Caption Data Synthesis, we
construct 1.2M semantically diverse high-quality captions by expanding sparse
caption seeds using large language models (LLMs). In Stage 2:
Instruction-Tuning Data Generation, we further process 471K captions into
multi-turn instruction-tuning tasks to support complex reasoning. Finally, in
Stage 3: Modality Representation Transfer, these textual captions
representations are transformed into visual representations, resulting in
diverse synthetic image representations. This three-stage process enables us to
construct Unicorn-1.2M for pretraining and Unicorn-471K-Instruction for
instruction-tuning, without relying on real images. By eliminating the
dependency on real images while maintaining data quality and diversity, our
framework offers a cost-effective and scalable solution for VLMs training. Code
is available at https://github.com/Yu-xm/Unicorn.git.
