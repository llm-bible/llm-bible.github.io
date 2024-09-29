---
layout: publication
title: Understanding Attention For Vision-and-language Tasks
authors: Cao Feiqi, Han Soyeon Caren, Long Siqu, Xu Changwei, Poon Josiah
conference: "Arxiv"
year: 2022
bibkey: cao2022understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08104"}
  - {name: "Code", url: "https://github.com/adlnlp/Attention\_VL"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Training Techniques', 'Transformer']
---
Attention mechanism has been used as an important component across Vision-and-Language(VL) tasks in order to bridge the semantic gap between visual and textual features. While attention has been widely used in VL tasks it has not been examined the capability of different attention alignment calculation in bridging the semantic gap between visual and textual clues. In this research we conduct a comprehensive analysis on understanding the role of attention alignment by looking into the attention score calculation methods and check how it actually represents the visual regions and textual tokens significance for the global assessment. We also analyse the conditions which attention score calculation mechanism would be more (or less) interpretable and which may impact the model performance on three different VL tasks including visual question answering text-to-image generation text-and-image matching (both sentence and image retrieval). Our analysis is the first of its kind and provides useful insights of the importance of each attention alignment score calculation when applied at the training phase of VL tasks commonly ignored in attention-based cross modal models and/or pretrained models. Our code is available at https://github.com/adlnlp/Attention\_VL
