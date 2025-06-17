---
layout: publication
title: 'Next-gpt: Any-to-any Multimodal LLM'
authors: Shengqiong Wu, Hao Fei, Leigang Qu, Wei Ji, Tat-seng Chua
conference: Arxiv
year: 2023
citations: 84
bibkey: wu2023next
additional_links:
- name: Paper
  url: https://arxiv.org/abs/2309.05519
- name: Code
  url: https://next-gpt.github.io/
tags:
- Multimodal Models
- GPT
- Reinforcement Learning
- Agentic
---
While recently Multimodal Large Language Models (MM-LLMs) have made exciting
strides, they mostly fall prey to the limitation of only input-side multimodal
understanding, without the ability to produce content in multiple modalities.
As we humans always perceive the world and communicate with people through
various modalities, developing any-to-any MM-LLMs capable of accepting and
delivering content in any modality becomes essential to human-level AI. To fill
the gap, we present an end-to-end general-purpose any-to-any MM-LLM system,
NExT-GPT. We connect an LLM with multimodal adaptors and different diffusion
decoders, enabling NExT-GPT to perceive inputs and generate outputs in
arbitrary combinations of text, images, videos, and audio. By leveraging the
existing well-trained highly-performing encoders and decoders, NExT-GPT is
tuned with only a small amount of parameter (1%) of certain projection layers,
which not only benefits low-cost training and also facilitates convenient
expansion to more potential modalities. Moreover, we introduce a
modality-switching instruction tuning (MosIT) and manually curate a
high-quality dataset for MosIT, based on which NExT-GPT is empowered with
complex cross-modal semantic understanding and content generation. Overall, our
research showcases the promising possibility of building an AI agent capable of
modeling universal modalities, paving the way for more human-like AI research
in the community. Project page: https://next-gpt.github.io/