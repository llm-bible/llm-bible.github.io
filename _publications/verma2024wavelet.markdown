---
layout: publication
title: 'Wavelet GPT: Wavelet Inspired Large Language Models'
authors: Prateek Verma
conference: "Arxiv"
year: 2024
bibkey: verma2024wavelet
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12924"}
tags: ['Pre-Training', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have ushered in a new wave of artificial
intelligence advancements impacting every scientific field and discipline. We
live in a world where most of the data around us, e.g., text, audio, and music,
has a multi-scale structure. This paper infuses LLMs with a traditional signal
processing idea, namely wavelets, during pre-training to take advantage of the
structure. Without adding \textbf\{any extra parameters\} to a GPT-style LLM
architecture in an academic setup, we achieve the same pre-training performance
almost twice as fast in text, audio, and images. This is done by imposing a
structure on intermediate embeddings. When trained for the same number of
training steps, we achieve significant gains in performance, which is
comparable to pre-training a larger neural architecture. Further, we show this
extends to the Long Range Arena benchmark and several input representations
such as characters, BPE tokens, bytes, waveform, math expression, and image
pixels. Our architecture allows every next token prediction access to
intermediate embeddings at different temporal resolutions in every decoder
block. We hope this will pave the way for incorporating multi-rate signal
processing into pre-training.
