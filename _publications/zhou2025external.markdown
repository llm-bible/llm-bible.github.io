---
layout: publication
title: 'External Knowledge Injection For Clip-based Class-incremental Learning'
authors: Da-wei Zhou, Kai-wen Li, Jingyi Ning, Han-jia Ye, Lijun Zhang, De-chuan Zhan
conference: "Arxiv"
year: 2025
bibkey: zhou2025external
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08510"}
  - {name: "Code", url: "https://github.com/RenaissCode/ENGINE"}
tags: ['Pre-Training', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Class-Incremental Learning (CIL) enables learning systems to continuously
adapt to evolving data streams. With the advancement of pre-training,
leveraging pre-trained vision-language models (e.g., CLIP) offers a promising
starting point for CIL. However, CLIP makes decisions by matching visual
embeddings to class names, overlooking the rich contextual information conveyed
through language. For instance, the concept of ``cat'' can be decomposed into
features like tail, fur, and face for recognition. Besides, since the model is
continually updated, these detailed features are overwritten in CIL, requiring
external knowledge for compensation. In this paper, we introduce ExterNal
knowledGe INjEction (ENGINE) for CLIP-based CIL. To enhance knowledge transfer
from outside the dataset, we propose a dual-branch injection tuning framework
that encodes informative knowledge from both visual and textual modalities. The
visual branch is enhanced with data augmentation to enrich the visual features,
while the textual branch leverages GPT-4 to rewrite discriminative descriptors.
In addition to this on-the-fly knowledge injection, we also implement
post-tuning knowledge by re-ranking the prediction results during inference.
With the injected knowledge, the model can better capture informative features
for downstream tasks as data evolves. Extensive experiments demonstrate the
state-of-the-art performance of ENGINE. Code is available at:
https://github.com/RenaissCode/ENGINE
