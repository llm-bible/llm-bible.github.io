---
layout: publication
title: 'Vlr-bench: Multilingual Benchmark Dataset For Vision-language Retrieval Augmented Generation'
authors: Hyeonseok Lim, Dongjae Shin, Seohyun Song, Inho Won, Minjun Kim, Junghun Yuk, Haneol Jang, Kyungtae Lim
conference: "Arxiv"
year: 2024
bibkey: lim2024vlr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10151"}
tags: ['RAG', 'Training Techniques', 'Applications', 'Multimodal Models']
---
We propose the VLR-Bench, a visual question answering (VQA) benchmark for
evaluating vision language models (VLMs) based on retrieval augmented
generation (RAG). Unlike existing evaluation datasets for external
knowledge-based VQA, the proposed VLR-Bench includes five input passages. This
allows testing of the ability to determine which passage is useful for
answering a given query, a capability lacking in previous research. In this
context, we constructed a dataset of 32,000 automatically generated
instruction-following examples, which we denote as VLR-IF. This dataset is
specifically designed to enhance the RAG capabilities of VLMs by enabling them
to learn how to generate appropriate answers based on input passages. We
evaluated the validity of the proposed benchmark and training data and verified
its performance using the state-of-the-art Llama3-based VLM, the Llava-Llama-3
model. The proposed VLR-Bench and VLR-IF datasets are publicly available
online.
