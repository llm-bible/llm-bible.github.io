---
layout: publication
title: 'VQGAN-CLIP: Open Domain Image Generation And Editing With Natural Language
  Guidance'
authors: Katherine Crowson et al.
conference: Arxiv
year: 2022
citations: 166
bibkey: crowson2022vqgan
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.08583'}]
tags: [Multimodal Models, Prompting]
---
Generating and editing images from open domain text prompts is a challenging
task that heretofore has required expensive and specially trained models. We
demonstrate a novel methodology for both tasks which is capable of producing
images of high visual quality from text prompts of significant semantic
complexity without any training by using a multimodal encoder to guide image
generations. We demonstrate on a variety of tasks how using CLIP [37] to guide
VQGAN [11] produces higher visual quality outputs than prior, less flexible
approaches like DALL-E [38], GLIDE [33] and Open-Edit [24], despite not being
trained for the tasks presented. Our code is available in a public repository.