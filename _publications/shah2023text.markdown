---
layout: publication
title: 'Parrottts: Text-to-speech Synthesis By Exploiting Self-supervised Representations'
authors: Neil Shah, Saiteja Kosgi, Vishal Tambrahalli, Neha Sahipjohn, Niranjan Pedanekar, Vineet Gandhi
conference: "Arxiv"
year: 2023
bibkey: shah2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.01261"}
tags: ['RAG', 'Training Techniques']
---
We present ParrotTTS, a modularized text-to-speech synthesis model leveraging
disentangled self-supervised speech representations. It can train a
multi-speaker variant effectively using transcripts from a single speaker.
ParrotTTS adapts to a new language in low resource setup and generalizes to
languages not seen while training the self-supervised backbone. Moreover,
without training on bilingual or parallel examples, ParrotTTS can transfer
voices across languages while preserving the speaker specific characteristics,
e.g., synthesizing fluent Hindi speech using a French speaker's voice and
accent. We present extensive results in monolingual and multi-lingual
scenarios. ParrotTTS outperforms state-of-the-art multi-lingual TTS models
using only a fraction of paired data as latter.
