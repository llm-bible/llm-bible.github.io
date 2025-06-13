---
layout: publication
title: 'Multilingual Encoder Knows More Than You Realize: Shared Weights Pretraining For Extremely Low-resource Languages'
authors: Zeli Su, Ziyin Zhang, Guixian Xu, Jianing Liu, Xu Han, Ting Zhang, Yushuang Dong
conference: "Arxiv"
year: 2025
bibkey: su2025multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10852"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Applications']
---
While multilingual language models like XLM-R have advanced multilingualism in NLP, they still perform poorly in extremely low-resource languages. This situation is exacerbated by the fact that modern LLMs such as LLaMA and Qwen support far fewer languages than XLM-R, making text generation models non-existent for many languages in the world. To tackle this challenge, we propose a novel framework for adapting multilingual encoders to text generation in extremely low-resource languages. By reusing the weights between the encoder and the decoder, our framework allows the model to leverage the learned semantic space of the encoder, enabling efficient learning and effective generalization in low-resource languages. Applying this framework to four Chinese minority languages, we present XLM-SWCM, and demonstrate its superior performance on various downstream tasks even when compared with much larger models.
