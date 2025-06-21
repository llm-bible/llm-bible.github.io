---
layout: publication
title: 'Seamless: Multilingual Expressive And Streaming Speech Translation'
authors: Seamless Communication et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: communication2023multilingual
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.05187'}, {name: Code,
    url: 'https://github.com/facebookresearch/seamless_communication'}]
tags: [Ethics and Bias, Multimodal Models, Transformer, Tools]
---
Large-scale automatic speech translation systems today lack key features that
help machine-mediated communication feel seamless when compared to
human-to-human dialogue. In this work, we introduce a family of models that
enable end-to-end expressive and multilingual translations in a streaming
fashion. First, we contribute an improved version of the massively multilingual
and multimodal SeamlessM4T model-SeamlessM4T v2. This newer model,
incorporating an updated UnitY2 framework, was trained on more low-resource
language data. SeamlessM4T v2 provides the foundation on which our next two
models are initiated. SeamlessExpressive enables translation that preserves
vocal styles and prosody. Compared to previous efforts in expressive speech
research, our work addresses certain underexplored aspects of prosody, such as
speech rate and pauses, while also preserving the style of one's voice. As for
SeamlessStreaming, our model leverages the Efficient Monotonic Multihead
Attention mechanism to generate low-latency target translations without waiting
for complete source utterances. As the first of its kind, SeamlessStreaming
enables simultaneous speech-to-speech/text translation for multiple source and
target languages. To ensure that our models can be used safely and responsibly,
we implemented the first known red-teaming effort for multimodal machine
translation, a system for the detection and mitigation of added toxicity, a
systematic evaluation of gender bias, and an inaudible localized watermarking
mechanism designed to dampen the impact of deepfakes. Consequently, we bring
major components from SeamlessExpressive and SeamlessStreaming together to form
Seamless, the first publicly available system that unlocks expressive
cross-lingual communication in real-time. The contributions to this work are
publicly released and accessible at
https://github.com/facebookresearch/seamless_communication