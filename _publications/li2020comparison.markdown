---
layout: publication
title: 'A Comparison Of Pre-trained Vision-and-language Models For Multimodal Representation Learning Across Medical Images And Reports'
authors: Yikuan Li, Hanyin Wang, Yuan Luo
conference: "Arxiv"
year: 2020
bibkey: li2020comparison
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2009.01523'}
tags: ['Attention Mechanism', 'BERT', 'Applications', 'Model Architecture', 'Multimodal Models']
---
Joint image-text embedding extracted from medical images and associated
contextual reports is the bedrock for most biomedical vision-and-language (V+L)
tasks, including medical visual question answering, clinical image-text
retrieval, clinical report auto-generation. In this study, we adopt four
pre-trained V+L models: LXMERT, VisualBERT, UNIER and PixelBERT to learn
multimodal representation from MIMIC-CXR radiographs and associated reports.
The extrinsic evaluation on OpenI dataset shows that in comparison to the
pioneering CNN-RNN model, the joint embedding learned by pre-trained V+L models
demonstrate performance improvement in the thoracic findings classification
task. We conduct an ablation study to analyze the contribution of certain model
components and validate the advantage of joint embedding over text-only
embedding. We also visualize attention maps to illustrate the attention
mechanism of V+L models.
