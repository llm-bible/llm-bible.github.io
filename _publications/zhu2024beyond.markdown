---
layout: publication
title: 'Beyond Text: Frozen Large Language Models In Visual Signal Comprehension'
authors: Lei Zhu, Fangyun Wei, Yanye Lu
conference: "Arxiv"
year: 2024
bibkey: zhu2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07874"}
  - {name: "Code", url: "https://github.com/zh460045050/V2L-Tokenizer"}
tags: ['Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
In this work, we investigate the potential of a large language model (LLM) to
directly comprehend visual signals without the necessity of fine-tuning on
multi-modal datasets. The foundational concept of our method views an image as
a linguistic entity, and translates it to a set of discrete words derived from
the LLM's vocabulary. To achieve this, we present the Vision-to-Language
Tokenizer, abbreviated as V2T Tokenizer, which transforms an image into a
``foreign language'' with the combined aid of an encoder-decoder, the LLM
vocabulary, and a CLIP model. With this innovative image encoding, the LLM
gains the ability not only for visual comprehension but also for image
denoising and restoration in an auto-regressive fashion-crucially, without any
fine-tuning. We undertake rigorous experiments to validate our method,
encompassing understanding tasks like image recognition, image captioning, and
visual question answering, as well as image denoising tasks like inpainting,
outpainting, deblurring, and shift restoration. Code and models are available
at https://github.com/zh460045050/V2L-Tokenizer.
