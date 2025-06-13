---
layout: publication
title: 'Low Frame-rate Speech Codec: A Codec Designed For Fast High-quality Speech LLM Training And Inference'
authors: Edresson Casanova, Ryan Langman, Paarth Neekhara, Shehzeen Hussain, Jason Li, Subhankar Ghosh, Ante Jukić, Sang-gil Lee
conference: "Arxiv"
year: 2024
bibkey: casanova2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12117"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Language Modeling', 'RAG', 'GPT', 'Quantization', 'Pretraining Methods']
---
Large language models (LLMs) have significantly advanced audio processing
through audio codecs that convert audio into discrete tokens, enabling the
application of language modeling techniques to audio data. However, audio
codecs often operate at high frame rates, resulting in slow training and
inference, especially for autoregressive models. To address this challenge, we
present the Low Frame-rate Speech Codec (LFSC): a neural audio codec that
leverages finite scalar quantization and adversarial training with large speech
language models to achieve high-quality audio compression with a 1.89 kbps
bitrate and 21.5 frames per second. We demonstrate that our novel codec can
make the inference of LLM-based text-to-speech models around three times faster
while improving intelligibility and producing quality comparable to previous
models.
