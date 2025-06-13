---
layout: publication
title: 'Bridging Speech And Text: Enhancing ASR With Pinyin-to-character Pre-training In Llms'
authors: Yang Yuhang, Peng Yizhou, Eng Siong Chng, Xionghu Zhong
conference: "Arxiv"
year: 2024
bibkey: yuhang2024bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.16005'}
tags: ['RAG', 'INTERSPEECH', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Pre-Training']
---
The integration of large language models (LLMs) with pre-trained speech
models has opened up new avenues in automatic speech recognition (ASR). While
LLMs excel in multimodal understanding tasks, effectively leveraging their
capabilities for ASR remains a significant challenge. This paper presents a
novel training approach to enhance LLM performance in ASR tasks. We propose
pre-training LLMs on Pinyin embedding sequences, which represent pronunciation
features, to generate corresponding Chinese characters. This step enables the
LLM to adapt to generating text from pronunciation features before encountering
real speech data. Furthermore, we fine-tune the LoRA parameters to enhance the
LLM's understanding of speech modality information. In AISHELL-1 corpus, our
approach yields a 9.5% relative improvement in ASR tasks compared to the
baseline without Pinyi-to-Character pre-training. Additionally, incorporating
auxiliary text data for Pinyi-to-Character pre-training further boosts
performance, achieving a 19.0% relative improvement.
