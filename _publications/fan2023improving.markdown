---
layout: publication
title: Improving CLIP Training With Language Rewrites
authors: Lijie Fan, Dilip Krishnan, Phillip Isola, Dina Katabi, Yonglong Tian
conference: Arxiv
year: 2023
citations: 24
bibkey: fan2023improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.20088'}, {name: Code,
    url: 'https://github.com/LijieFan/LaCLIP'}]
tags: [Pre-Training, In-Context Learning, RAG]
---
Contrastive Language-Image Pre-training (CLIP) stands as one of the most
effective and scalable methods for training transferable vision models using
paired image and text data. CLIP models are trained using contrastive loss,
which typically relies on data augmentations to prevent overfitting and
shortcuts. However, in the CLIP training paradigm, data augmentations are
exclusively applied to image inputs, while language inputs remain unchanged
throughout the entire training process, limiting the exposure of diverse texts
to the same image. In this paper, we introduce Language augmented CLIP
(LaCLIP), a simple yet highly effective approach to enhance CLIP training
through language rewrites. Leveraging the in-context learning capability of
large language models, we rewrite the text descriptions associated with each
image. These rewritten texts exhibit diversity in sentence structure and
vocabulary while preserving the original key concepts and meanings. During
training, LaCLIP randomly selects either the original texts or the rewritten
versions as text augmentations for each image. Extensive experiments on CC3M,
CC12M, RedCaps and LAION-400M datasets show that CLIP pre-training with
language rewrites significantly improves the transfer performance without
computation or memory overhead during training. Specifically for ImageNet
zero-shot accuracy, LaCLIP outperforms CLIP by 8.2% on CC12M and 2.4% on
LAION-400M. Code is available at https://github.com/LijieFan/LaCLIP.