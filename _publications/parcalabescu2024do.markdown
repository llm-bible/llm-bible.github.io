---
layout: publication
title: 'Do Vision & Language Decoders Use Images And Text Equally? How Self-consistent Are Their Explanations?'
authors: Parcalabescu Letitia, Frank Anette
conference: "Arxiv"
year: 2024
bibkey: parcalabescu2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18624"}
tags: ['Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Vision and language model (VLM) decoders are currently the best-performing architectures on multimodal tasks. Next to predictions they can also produce explanations either in post-hoc or CoT settings. However it is not clear how much they use the vision and text modalities when generating predictions or explanations. In this work we investigate if VLMs rely on modalities differently when they produce explanations as opposed to providing answers. We also evaluate the self-consistency of VLM decoders in both post-hoc and CoT explanation settings by extending existing unimodal tests and measures to VLM decoders. We find that VLMs are less self-consistent than LLMs. Text contributions in VL decoders are more important than image contributions in all examined tasks. Moreover the contributions of images are significantly stronger for explanation generation compared to answer generation. This difference is even larger in CoT compared to post-hoc explanations. Lastly we provide an up-to-date benchmarking of state-of-the-art VL decoders on the VALSE benchmark which before only covered VL encoders. We find that VL decoders still struggle with most phenomena tested by VALSE.
