---
layout: publication
title: 'Styledrop: Text-to-image Generation In Any Style'
authors: Kihyuk Sohn et al.
conference: Arxiv
year: 2023
citations: 23
bibkey: sohn2023text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.00983'}]
tags: [Fine-Tuning, Prompting, RAG]
---
Pre-trained large text-to-image models synthesize impressive images with an
appropriate use of text prompts. However, ambiguities inherent in natural
language and out-of-distribution effects make it hard to synthesize image
styles, that leverage a specific design pattern, texture or material. In this
paper, we introduce StyleDrop, a method that enables the synthesis of images
that faithfully follow a specific style using a text-to-image model. The
proposed method is extremely versatile and captures nuances and details of a
user-provided style, such as color schemes, shading, design patterns, and local
and global effects. It efficiently learns a new style by fine-tuning very few
trainable parameters (less than \\(1%\\) of total model parameters) and improving
the quality via iterative training with either human or automated feedback.
Better yet, StyleDrop is able to deliver impressive results even when the user
supplies only a single image that specifies the desired style. An extensive
study shows that, for the task of style tuning text-to-image models, StyleDrop
implemented on Muse convincingly outperforms other methods, including
DreamBooth and textual inversion on Imagen or Stable Diffusion. More results
are available at our project website: https://styledrop.github.io