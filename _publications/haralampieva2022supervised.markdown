---
layout: publication
title: 'Supervised Visual Attention For Simultaneous Multimodal Machine Translation'
authors: Veneta Haralampieva, Ozan Caglayan, Lucia Specia
conference: "Journal of Artificial Intelligence Research 74 (2022) 1059-1089"
year: 2022
bibkey: haralampieva2022supervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.09324"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Applications', 'Attention Mechanism']
---
Recently, there has been a surge in research in multimodal machine
translation (MMT), where additional modalities such as images are used to
improve translation quality of textual systems. A particular use for such
multimodal systems is the task of simultaneous machine translation, where
visual context has been shown to complement the partial information provided by
the source sentence, especially in the early phases of translation. In this
paper, we propose the first Transformer-based simultaneous MMT architecture,
which has not been previously explored in the field. Additionally, we extend
this model with an auxiliary supervision signal that guides its visual
attention mechanism using labelled phrase-region alignments. We perform
comprehensive experiments on three language directions and conduct thorough
quantitative and qualitative analyses using both automatic metrics and manual
inspection. Our results show that (i) supervised visual attention consistently
improves the translation quality of the MMT models, and (ii) fine-tuning the
MMT with supervision loss enabled leads to better performance than training the
MMT from scratch. Compared to the state-of-the-art, our proposed model achieves
improvements of up to 2.3 BLEU and 3.5 METEOR points.
