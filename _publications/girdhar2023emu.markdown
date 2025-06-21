---
layout: publication
title: 'Emu Video: Factorizing Text-to-video Generation By Explicit Image Conditioning'
authors: Rohit Girdhar et al.
conference: Arxiv
year: 2023
citations: 21
bibkey: girdhar2023emu
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.10709'}]
tags: [Prompting]
---
We present Emu Video, a text-to-video generation model that factorizes the
generation into two steps: first generating an image conditioned on the text,
and then generating a video conditioned on the text and the generated image. We
identify critical design decisions--adjusted noise schedules for diffusion, and
multi-stage training that enable us to directly generate high quality and high
resolution videos, without requiring a deep cascade of models as in prior work.
In human evaluations, our generated videos are strongly preferred in quality
compared to all prior work--81% vs. Google's Imagen Video, 90% vs. Nvidia's
PYOCO, and 96% vs. Meta's Make-A-Video. Our model outperforms commercial
solutions such as RunwayML's Gen2 and Pika Labs. Finally, our factorizing
approach naturally lends itself to animating images based on a user's text
prompt, where our generations are preferred 96% over prior work.