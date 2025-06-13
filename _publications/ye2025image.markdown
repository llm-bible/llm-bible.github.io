---
layout: publication
title: 'IDEA: Image Description Enhanced Clip-adapter'
authors: Zhipeng Ye, Feng Jiang, Qiufeng Wang, Kaizhu Huang, Jiaqi Huang
conference: "Arxiv"
year: 2025
bibkey: ye2025image
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.08816'}
  - {name: "Code", url: 'https://github.com/FourierAI/IDEA'}
tags: ['Has Code', 'Few-Shot', 'RAG', 'Training Techniques', 'Prompting', 'Multimodal Models', 'Pre-Training']
---
CLIP (Contrastive Language-Image Pre-training) has attained great success in
pattern recognition and computer vision. Transferring CLIP to downstream tasks
(e.g. zero- or few-shot classification) is a hot topic in multimodal learning.
However, current studies primarily focus on either prompt learning for text or
adapter tuning for vision, without fully exploiting the complementary
information and correlations among image-text pairs. In this paper, we propose
an Image Description Enhanced CLIP-Adapter (IDEA) method to adapt CLIP to
few-shot image classification tasks. This method captures fine-grained features
by leveraging both visual features and textual descriptions of images. IDEA is
a training-free method for CLIP, and it can be comparable to or even exceeds
state-of-the-art models on multiple tasks. Furthermore, we introduce
Trainable-IDEA (T-IDEA), which extends IDEA by adding two lightweight learnable
components (i.e., a projector and a learnable latent space), further enhancing
the model's performance and achieving SOTA results on 11 datasets. As one
important contribution, we employ the Llama model and design a comprehensive
pipeline to generate textual descriptions for images of 11 datasets, resulting
in a total of 1,637,795 image-text pairs, named "IMD-11". Our code and data are
released at https://github.com/FourierAI/IDEA.
