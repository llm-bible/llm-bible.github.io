---
layout: publication
title: 'Generating Data With Text-to-speech And Large-language Models For Conversational Speech Recognition'
authors: Samuele Cornell, Jordan Darefsky, Zhiyao Duan, Shinji Watanabe
conference: "Arxiv"
year: 2024
bibkey: cornell2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09215"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'INTERSPEECH']
---
Currently, a common approach in many speech processing tasks is to leverage
large scale pre-trained models by fine-tuning them on in-domain data for a
particular application. Yet obtaining even a small amount of such data can be
problematic, especially for sensitive domains and conversational speech
scenarios, due to both privacy issues and annotation costs. To address this,
synthetic data generation using single speaker datasets has been employed. Yet,
for multi-speaker cases, such an approach often requires extensive manual
effort and is prone to domain mismatches. In this work, we propose a synthetic
data generation pipeline for multi-speaker conversational ASR, leveraging a
large language model (LLM) for content creation and a conversational
multi-speaker text-to-speech (TTS) model for speech synthesis. We conduct
evaluation by fine-tuning the Whisper ASR model for telephone and distant
conversational speech settings, using both in-domain data and generated
synthetic data. Our results show that the proposed method is able to
significantly outperform classical multi-speaker generation approaches that use
external, non-conversational speech datasets.
