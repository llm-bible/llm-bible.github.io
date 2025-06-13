---
layout: publication
title: 'AMO Sampler: Enhancing Text Rendering With Overshooting'
authors: Xixi Hu, Keyang Xu, Bo Liu, Qiang Liu, Hongliang Fei
conference: "Arxiv"
year: 2024
bibkey: hu2024amo
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19415'}
  - {name: "Code", url: 'https://github.com/hxixixh/amo-release'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Model Architecture', 'Merging', 'Reinforcement Learning']
---
Achieving precise alignment between textual instructions and generated images
in text-to-image generation is a significant challenge, particularly in
rendering written text within images. Sate-of-the-art models like Stable
Diffusion 3 (SD3), Flux, and AuraFlow still struggle with accurate text
depiction, resulting in misspelled or inconsistent text. We introduce a
training-free method with minimal computational overhead that significantly
enhances text rendering quality. Specifically, we introduce an overshooting
sampler for pretrained rectified flow (RF) models, by alternating between
over-simulating the learned ordinary differential equation (ODE) and
reintroducing noise. Compared to the Euler sampler, the overshooting sampler
effectively introduces an extra Langevin dynamics term that can help correct
the compounding error from successive Euler steps and therefore improve the
text rendering. However, when the overshooting strength is high, we observe
over-smoothing artifacts on the generated images. To address this issue, we
propose an Attention Modulated Overshooting sampler (AMO), which adaptively
controls the strength of overshooting for each image patch according to their
attention score with the text content. AMO demonstrates a 32.3% and 35.9%
improvement in text rendering accuracy on SD3 and Flux without compromising
overall image quality or increasing inference cost. Code available at:
https://github.com/hxixixh/amo-release.
