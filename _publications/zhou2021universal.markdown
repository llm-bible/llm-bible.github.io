---
layout: publication
title: 'UC2: Universal Cross-lingual Cross-modal Vision-and-language Pre-training'
authors: Mingyang Zhou et al.
conference: Arxiv
year: 2021
citations: 40
bibkey: zhou2021universal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.00332'}]
tags: [Multimodal Models, Pre-Training, Language Modeling]
---
Vision-and-language pre-training has achieved impressive success in learning
multimodal representations between vision and language. To generalize this
success to non-English languages, we introduce UC2, the first machine
translation-augmented framework for cross-lingual cross-modal representation
learning. To tackle the scarcity problem of multilingual captions for image
datasets, we first augment existing English-only datasets with other languages
via machine translation (MT). Then we extend the standard Masked Language
Modeling and Image-Text Matching training objectives to multilingual setting,
where alignment between different languages is captured through shared visual
context (i.e, using image as pivot). To facilitate the learning of a joint
embedding space of images and all languages of interest, we further propose two
novel pre-training tasks, namely Masked Region-to-Token Modeling (MRTM) and
Visual Translation Language Modeling (VTLM), leveraging MT-enhanced translated
data. Evaluation on multilingual image-text retrieval and multilingual visual
question answering benchmarks demonstrates that our proposed framework achieves
new state-of-the-art on diverse non-English benchmarks while maintaining
comparable performance to monolingual pre-trained models on English tasks.