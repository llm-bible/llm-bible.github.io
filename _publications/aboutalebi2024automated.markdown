---
layout: publication
title: 'MAGID: An Automated Pipeline For Generating Synthetic Multi-modal Datasets'
authors: Hossein Aboutalebi, Hwanjun Song, Yusheng Xie, Arshit Gupta, Justin Sun, Hang Su, Igor Shalyminov, Nikolaos Pappas, Siffi Singh, Saab Mansour
conference: "Arxiv"
year: 2024
bibkey: aboutalebi2024automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.03194'}
tags: ['Multimodal Models', 'Responsible AI', 'Tools', 'Merging']
---
Development of multimodal interactive systems is hindered by the lack of
rich, multimodal (text, images) conversational data, which is needed in large
quantities for LLMs. Previous approaches augment textual dialogues with
retrieved images, posing privacy, diversity, and quality constraints. In this
work, we introduce Multimodal Augmented Generative Images Dialogues (MAGID), a
framework to augment text-only dialogues with diverse and high-quality images.
Subsequently, a diffusion model is applied to craft corresponding images,
ensuring alignment with the identified text. Finally, MAGID incorporates an
innovative feedback loop between an image description generation module
(textual LLM) and image quality modules (addressing aesthetics, image-text
matching, and safety), that work in tandem to generate high-quality and
multi-modal dialogues. We compare MAGID to other SOTA baselines on three
dialogue datasets, using automated and human evaluation. Our results show that
MAGID is comparable to or better than baselines, with significant improvements
in human evaluation, especially against retrieval baselines where the image
database is small.
