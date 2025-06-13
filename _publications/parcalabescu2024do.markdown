---
layout: publication
title: 'Do Vision & Language Decoders Use Images And Text Equally? How Self-consistent Are Their Explanations?'
authors: Letitia Parcalabescu, Anette Frank
conference: "Arxiv"
year: 2024
bibkey: parcalabescu2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18624"}
tags: ['Interpretability and Explainability', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning']
---
Vision and language model (VLM) decoders are currently the best-performing
architectures on multimodal tasks. Next to answers, they are able to produce
natural language explanations, either in post-hoc or CoT settings. However, it
is not clear to what extent they are using the input vision and text modalities
when generating answers or explanations. In this work, we investigate if VLMs
rely on their input modalities differently when they produce explanations as
opposed to answers. We also evaluate the self-consistency of VLM decoders in
both post-hoc and CoT explanation settings, by extending existing unimodal
tests and measures to VLM decoders. We find that most tested VLMs are less
self-consistent than LLMs. Text contributions in all tested VL decoders are
more important than image contributions in all examined tasks. However, when
comparing explanation generation to answer generation, the contributions of
images are significantly stronger for generating explanations compared to
answers. This difference is even larger in CoT compared to post-hoc
explanations. Lastly, we provide an up-to-date benchmarking of state-of-the-art
VL decoders on the VALSE benchmark, which before was restricted to VL encoders.
We find that the tested VL decoders still struggle with most phenomena tested
by VALSE.
