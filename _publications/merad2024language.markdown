---
layout: publication
title: 'Language Very Rare For All'
authors: Ibrahim Merad, Amos Wolf, Ziad Mazzawi, Yannick Léo
conference: "Arxiv"
year: 2024
bibkey: merad2024language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.13924'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
In the quest to overcome language barriers, encoder-decoder models like NLLB
have expanded machine translation to rare languages, with some models (e.g.,
NLLB 1.3B) even trainable on a single GPU. While general-purpose LLMs perform
well in translation, open LLMs prove highly competitive when fine-tuned for
specific tasks involving unknown corpora. We introduce LYRA (Language verY Rare
for All), a novel approach that combines open LLM fine-tuning,
retrieval-augmented generation (RAG), and transfer learning from related
high-resource languages. This study is exclusively focused on single-GPU
training to facilitate ease of adoption. Our study focuses on two-way
translation between French and Mon\'egasque, a rare language unsupported by
existing translation tools due to limited corpus availability. Our results
demonstrate LYRA's effectiveness, frequently surpassing and consistently
matching state-of-the-art encoder-decoder models in rare language translation.
