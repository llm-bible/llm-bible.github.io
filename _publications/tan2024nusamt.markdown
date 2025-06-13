---
layout: publication
title: 'Nusamt-7b: Machine Translation For Low-resource Indonesian Languages With Large Language Models'
authors: William Tan, Kevin Zhu
conference: "Arxiv"
year: 2024
bibkey: tan2024nusamt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07830"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Large Language Models (LLMs) have demonstrated exceptional promise in
translation tasks for high-resource languages. However, their performance in
low-resource languages is limited by the scarcity of both parallel and
monolingual corpora, as well as the presence of noise. Consequently, such LLMs
suffer with alignment and have lagged behind State-of-The-Art (SoTA) neural
machine translation (NMT) models in these settings. This paper introduces
NusaMT-7B, an LLM-based machine translation model for low-resource Indonesian
languages, starting with Balinese and Minangkabau. Leveraging the pretrained
LLaMA2-7B, our approach integrates continued pre-training on monolingual data,
Supervised Fine-Tuning (SFT), self-learning, and an LLM-based data cleaner to
reduce noise in parallel sentences. In the FLORES-200 multilingual translation
benchmark, NusaMT-7B outperforms SoTA models in the spBLEU metric by up to
+6.69 spBLEU in translations into Balinese and Minangkabau, but underperforms
by up to -3.38 spBLEU in translations into higher-resource languages. Our
results show that fine-tuned LLMs can enhance translation quality for
low-resource languages, aiding in linguistic preservation and cross-cultural
communication.
