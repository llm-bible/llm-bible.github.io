---
layout: publication
title: 'Group Diffusion Transformers Are Unsupervised Multitask Learners'
authors: Lianghua Huang, Wei Wang, Zhi-fan Wu, Huanzhang Dou, Yupeng Shi, Yutong Feng, Chen Liang, Yu Liu, Jingren Zhou
conference: "Arxiv"
year: 2024
bibkey: huang2024group
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15027'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Merging', 'Multimodal Models', 'Pretraining Methods']
---
While large language models (LLMs) have revolutionized natural language
processing with their task-agnostic capabilities, visual generation tasks such
as image translation, style transfer, and character customization still rely
heavily on supervised, task-specific datasets. In this work, we introduce Group
Diffusion Transformers (GDTs), a novel framework that unifies diverse visual
generation tasks by redefining them as a group generation problem. In this
approach, a set of related images is generated simultaneously, optionally
conditioned on a subset of the group. GDTs build upon diffusion transformers
with minimal architectural modifications by concatenating self-attention tokens
across images. This allows the model to implicitly capture cross-image
relationships (e.g., identities, styles, layouts, surroundings, and color
schemes) through caption-based correlations. Our design enables scalable,
unsupervised, and task-agnostic pretraining using extensive collections of
image groups sourced from multimodal internet articles, image galleries, and
video frames. We evaluate GDTs on a comprehensive benchmark featuring over 200
instructions across 30 distinct visual generation tasks, including picture book
creation, font design, style transfer, sketching, colorization, drawing
sequence generation, and character customization. Our models achieve
competitive zero-shot performance without any additional fine-tuning or
gradient updates. Furthermore, ablation studies confirm the effectiveness of
key components such as data scaling, group size, and model design. These
results demonstrate the potential of GDTs as scalable, general-purpose visual
generation systems.
