---
layout: publication
title: 'TLAC: Two-stage LMM Augmented CLIP For Zero-shot Classification'
authors: Ans Munir, Faisal Z. Qureshi, Muhammad Haris Khan, Mohsen Ali
conference: "Arxiv"
year: 2025
bibkey: munir2025two
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12206'}
  - {name: "Code", url: 'https://github.com/ans92/TLAC'}
tags: ['Has Code', 'Few-Shot', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
Contrastive Language-Image Pretraining (CLIP) has shown impressive zero-shot
performance on image classification. However, state-of-the-art methods often
rely on fine-tuning techniques like prompt learning and adapter-based tuning to
optimize CLIP's performance. The necessity for fine-tuning significantly limits
CLIP's adaptability to novel datasets and domains. This requirement mandates
substantial time and computational resources for each new dataset. To overcome
this limitation, we introduce simple yet effective training-free approaches,
Single-stage LMM Augmented CLIP (SLAC) and Two-stage LMM Augmented CLIP (TLAC),
that leverages powerful Large Multimodal Models (LMMs), such as Gemini, for
image classification. The proposed methods leverages the capabilities of
pre-trained LMMs, allowing for seamless adaptation to diverse datasets and
domains without the need for additional training. Our approaches involve
prompting the LMM to identify objects within an image. Subsequently, the CLIP
text encoder determines the image class by identifying the dataset class with
the highest semantic similarity to the LLM predicted object. Our models
achieved superior accuracy on 9 of 11 base-to-novel datasets, including
ImageNet, SUN397, and Caltech101, while maintaining a strictly training-free
paradigm. Our TLAC model achieved an overall accuracy of 83.44%, surpassing the
previous state-of-the-art few-shot methods by a margin of 6.75%. Compared to
other training-free approaches, our TLAC method achieved 83.6% average accuracy
across 13 datasets, a 9.7% improvement over the previous methods. Our Code is
available at https://github.com/ans92/TLAC
