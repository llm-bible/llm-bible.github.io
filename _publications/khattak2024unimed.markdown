---
layout: publication
title: 'Unimed-clip: Towards A Unified Image-text Pretraining Paradigm For Diverse Medical Imaging Modalities'
authors: Muhammad Uzair Khattak, Shahina Kunhimon, Muzammal Naseer, Salman Khan, Fahad Shahbaz Khan
conference: "Arxiv"
year: 2024
bibkey: khattak2024unimed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10372'}
  - {name: "Code", url: 'https://github.com/mbzuai-oryx/UniMed-CLIP'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Tools', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Vision-Language Models (VLMs) trained via contrastive learning have achieved
notable success in natural image tasks. However, their application in the
medical domain remains limited due to the scarcity of openly accessible,
large-scale medical image-text datasets. Existing medical VLMs either train on
closed-source proprietary or relatively small open-source datasets that do not
generalize well. Similarly, most models remain specific to a single or limited
number of medical imaging domains, again restricting their applicability to
other modalities. To address this gap, we introduce UniMed, a large-scale,
open-source multi-modal medical dataset comprising over 5.3 million image-text
pairs across six diverse imaging modalities: X-ray, CT, MRI, Ultrasound,
Pathology, and Fundus. UniMed is developed using a data-collection framework
that leverages Large Language Models (LLMs) to transform modality-specific
classification datasets into image-text formats while incorporating existing
image-text data from the medical domain, facilitating scalable VLM pretraining.
Using UniMed, we trained UniMed-CLIP, a unified VLM for six modalities that
significantly outperforms existing generalist VLMs and matches
modality-specific medical VLMs, achieving notable gains in zero-shot
evaluations. For instance, UniMed-CLIP improves over BiomedCLIP (trained on
proprietary data) by an absolute gain of +12.61, averaged over 21 datasets,
while using 3x less training data. To facilitate future research, we release
UniMed dataset, training codes, and models at
https://github.com/mbzuai-oryx/UniMed-CLIP.
