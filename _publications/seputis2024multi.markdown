---
layout: publication
title: 'Multi-modal Adapter For Vision-language Models'
authors: Seputis Dominykas, Mihailov Serghei, Chatterjee Soham, Xiao Zehao
conference: "Arxiv"
year: 2024
bibkey: seputis2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02958"}
tags: ['Attention Mechanism', 'Few Shot', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
Large pre-trained vision-language models such as CLIP have demonstrated state-of-the-art performance across a wide range of image classification tasks without requiring retraining. Few-shot CLIP is competitive with existing specialized architectures that were trained on the downstream tasks. Recent research demonstrates that the performance of CLIP can be further improved using lightweight adaptation approaches. However previous methods adapt different modalities of the CLIP model individually ignoring the interactions and relationships between visual and textual representations. In this work we propose Multi-Modal Adapter an approach for Multi-Modal adaptation of CLIP. Specifically we add a trainable Multi-Head Attention layer that combines text and image features to produce an additive adaptation of both. Multi-Modal Adapter demonstrates improved generalizability based on its performance on unseen classes compared to existing adaptation methods. We perform additional ablations and investigations to validate and interpret the proposed approach.
