---
layout: publication
title: 'Dual-pipeline With Low-rank Adaptation For New Language Integration In Multilingual ASR'
authors: Yerbolat Khassanov, Zhipeng Chen, Tianfeng Chen, Tze Yuang Chong, Wei Li, Jun Zhang, Lu Lu, Yuxuan Wang
conference: "Arxiv"
year: 2024
bibkey: khassanov2024dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07842"}
tags: ['Fine-Tuning', 'Training Techniques', 'INTERSPEECH', 'Reinforcement Learning']
---
This paper addresses challenges in integrating new languages into a
pre-trained multilingual automatic speech recognition (mASR) system,
particularly in scenarios where training data for existing languages is limited
or unavailable. The proposed method employs a dual-pipeline with low-rank
adaptation (LoRA). It maintains two data flow pipelines-one for existing
languages and another for new languages. The primary pipeline follows the
standard flow through the pre-trained parameters of mASR, while the secondary
pipeline additionally utilizes language-specific parameters represented by LoRA
and a separate output decoder module. Importantly, the proposed approach
minimizes the performance degradation of existing languages and enables a
language-agnostic operation mode, facilitated by a decoder selection strategy.
We validate the effectiveness of the proposed method by extending the
pre-trained Whisper model to 19 new languages from the FLEURS dataset
