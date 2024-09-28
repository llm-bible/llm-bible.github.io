---
layout: publication
title: Discrete Multimodal Transformers with a Pretrained Large Language Model for Mixed-Supervision Speech Processing
authors: Trinh Viet Anh, Southwell Rosy, Guan Yiwen, He Xinlu, Wang Zhiyong, Whitehill Jacob
conference: "Arxiv"
year: 2024
bibkey: trinh2024discrete
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06582"}
tags: ['ARXIV', 'LLM', 'Model Architecture', 'Supervised', 'Transformer', 'Unsupervised']
---
Recent work on discrete speech tokenization has paved the way for models that can seamlessly perform multiple tasks across modalities e.g. speech recognition text to speech speech to speech translation. Moreover large language models (LLMs) pretrained from vast text corpora contain rich linguistic information that can improve accuracy in a variety of tasks. In this paper we present a decoder-only Discrete Multimodal Language Model (DMLM) which can be flexibly applied to multiple tasks (ASR T2S S2TT etc.) and modalities (text speech vision). We explore several critical aspects of discrete multi-modal models including the loss function weight initialization mixed training supervision and codebook. Our results show that DMLM benefits significantly across multiple tasks and datasets from a combination of supervised and unsupervised training. Moreover for ASR it benefits from initializing DMLM from a pretrained LLM and from a codebook derived from Whisper activations.
