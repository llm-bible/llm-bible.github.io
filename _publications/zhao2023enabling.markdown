---
layout: publication
title: 'Bubogpt: Enabling Visual Grounding In Multi-modal Llms'
authors: Yang Zhao et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: zhao2023enabling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.08581'}, {name: Code,
    url: 'https://bubo-gpt.github.io'}]
tags: [Multimodal Models, GPT]
---
LLMs have demonstrated remarkable abilities at interacting with humans
through language, especially with the usage of instruction-following data.
Recent advancements in LLMs, such as MiniGPT-4, LLaVA, and X-LLM, further
enlarge their abilities by incorporating multi-modal inputs, including image,
video, and speech. Despite their effectiveness at generating precise and
detailed language understanding of the given modality signal, these LLMs give
up the ability to ground specific parts of inputs, thus only constructing a
coarse-grained mapping. However, explicit and informative correspondence
between text and other modalities will not only improve the user experience but
also help to expand the application scenario of multi-modal LLMs. Therefore, we
propose BuboGPT, a multi-modal LLM with visual grounding that can perform
cross-modal interaction between vision, audio and language, providing
fine-grained understanding of visual objects and other given modalities. As a
result, BuboGPT is able to point out the specific location of an object in the
image, when it is generating response or description for that object. Our
contributions are two-fold: 1) An off-the-shelf visual grounding module based
on SAM that extracts entities in a sentence and find corresponding masks in the
image. 2) A two-stage training scheme and instruction dataset to endow joint
text-image-audio understanding. Our experiments show that BuboGPT achieves
impressive multi-modality understanding and visual grounding abilities during
the interaction with human. It performs consistently well when provided by
arbitrary modality combinations (either aligned or unaligned). Our code, model
and dataset are available at https://bubo-gpt.github.io .