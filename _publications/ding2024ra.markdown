---
layout: publication
title: 'RA-BLIP: Multimodal Adaptive Retrieval-augmented Bootstrapping Language-image Pre-training'
authors: Muhe Ding, Yang Ma, Pengda Qin, Jianlong Wu, Yuhong Li, Liqiang Nie
conference: "Arxiv"
year: 2024
bibkey: ding2024ra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14154"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'RAG', 'Merging', 'Interpretability and Explainability', 'Pre-Training']
---
Multimodal Large Language Models (MLLMs) have recently received substantial
interest, which shows their emerging potential as general-purpose models for
various vision-language tasks. MLLMs involve significant external knowledge
within their parameters; however, it is challenging to continually update these
models with the latest knowledge, which involves huge computational costs and
poor interpretability. Retrieval augmentation techniques have proven to be
effective plugins for both LLMs and MLLMs. In this study, we propose multimodal
adaptive Retrieval-Augmented Bootstrapping Language-Image Pre-training
(RA-BLIP), a novel retrieval-augmented framework for various MLLMs. Considering
the redundant information within vision modality, we first leverage the
question to instruct the extraction of visual information through interactions
with one set of learnable queries, minimizing irrelevant interference during
retrieval and generation. Besides, we introduce a pre-trained multimodal
adaptive fusion module to achieve question text-to-multimodal retrieval and
integration of multimodal knowledge by projecting visual and language
modalities into a unified semantic space. Furthermore, we present an Adaptive
Selection Knowledge Generation (ASKG) strategy to train the generator to
autonomously discern the relevance of retrieved knowledge, which realizes
excellent denoising performance. Extensive experiments on open multimodal
question-answering datasets demonstrate that RA-BLIP achieves significant
performance and surpasses the state-of-the-art retrieval-augmented models.
