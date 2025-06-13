---
layout: publication
title: 'Speechgpt-gen: Scaling Chain-of-information Speech Generation'
authors: Dong Zhang, Xin Zhang, Jun Zhan, Shimin Li, Yaqian Zhou, Xipeng Qiu
conference: "Arxiv"
year: 2024
bibkey: zhang2024speechgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13527"}
  - {name: "Code", url: "https://github.com/0nutation/SpeechGPT"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Has Code']
---
Benefiting from effective speech modeling, current Speech Large Language
Models (SLLMs) have demonstrated exceptional capabilities in in-context speech
generation and efficient generalization to unseen speakers. However, the
prevailing information modeling process is encumbered by certain redundancies,
leading to inefficiencies in speech generation. We propose Chain-of-Information
Generation (CoIG), a method for decoupling semantic and perceptual information
in large-scale speech generation. Building on this, we develop SpeechGPT-Gen,
an 8-billion-parameter SLLM efficient in semantic and perceptual information
modeling. It comprises an autoregressive model based on LLM for semantic
information modeling and a non-autoregressive model employing flow matching for
perceptual information modeling. Additionally, we introduce the novel approach
of infusing semantic information into the prior distribution to enhance the
efficiency of flow matching. Extensive experimental results demonstrate that
SpeechGPT-Gen markedly excels in zero-shot text-to-speech, zero-shot voice
conversion, and speech-to-speech dialogue, underscoring CoIG's remarkable
proficiency in capturing and modeling speech's semantic and perceptual
dimensions. Code and models are available at
https://github.com/0nutation/SpeechGPT.
