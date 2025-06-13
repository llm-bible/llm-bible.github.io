---
layout: publication
title: 'Diffusion Language Models Generation Can Be Halted Early'
authors: Sofia Maria Lo Cicero Vaina, Nikita Balagansky, Daniil Gavrilov
conference: "Arxiv"
year: 2023
bibkey: vaina2023diffusion
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.10818'}
tags: ['Language Modeling', 'GPT', 'Applications', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Diffusion Language models (DLMs) are a promising avenue for text generation
due to their practical properties on tractable controllable generation. They
also have the advantage of not having to predict text autoregressively.
However, despite these notable features, DLMs have not yet reached the
performance levels of their autoregressive counterparts. One of the ways to
reduce the performance gap between these two types of language models is to
speed up the generation of DLMs. Therefore, we propose a novel methodology to
address this issue in this work. It enables the execution of more generation
steps within a given time frame, leading to higher-quality outputs.
Specifically, our methods estimate DLMs completeness of text generation and
allow adaptive halting of the generation process. We evaluate our methods on
Plaid, SSD, and CDCD DLMs and create a cohesive perspective on their generation
workflows. Finally, we confirm that our methods allow halting these models and
decrease the generation time by \\(10\\)-\\(40\\)% without a drop in the quality of
model samples.
