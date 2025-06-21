---
layout: publication
title: 'CLIPTER: Looking At The Bigger Picture In Scene Text Recognition'
authors: Aviad Aberdam et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: aberdam2023looking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.07464'}]
tags: [Fine-Tuning, Multimodal Models, Attention Mechanism]
---
Reading text in real-world scenarios often requires understanding the context
surrounding it, especially when dealing with poor-quality text. However,
current scene text recognizers are unaware of the bigger picture as they
operate on cropped text images. In this study, we harness the representative
capabilities of modern vision-language models, such as CLIP, to provide
scene-level information to the crop-based recognizer. We achieve this by fusing
a rich representation of the entire image, obtained from the vision-language
model, with the recognizer word-level features via a gated cross-attention
mechanism. This component gradually shifts to the context-enhanced
representation, allowing for stable fine-tuning of a pretrained recognizer. We
demonstrate the effectiveness of our model-agnostic framework, CLIPTER (CLIP
TExt Recognition), on leading text recognition architectures and achieve
state-of-the-art results across multiple benchmarks. Furthermore, our analysis
highlights improved robustness to out-of-vocabulary words and enhanced
generalization in low-data regimes.