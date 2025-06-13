---
layout: publication
title: 'Ichigo: Mixed-modal Early-fusion Realtime Voice Assistant'
authors: Alan Gia Tuan Dao Dao, Dinh Bach Vu, Huy Hoang Ha
conference: "Arxiv"
year: 2024
bibkey: dao2024mixed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.15316'}
tags: ['Transformer', 'INTERSPEECH', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large Language Models (LLMs) have revolutionized natural language processing,
but their application to speech-based tasks remains challenging due to the
complexities of integrating audio and text modalities. This paper introduces
Ichigo, a mixed-modal model that seamlessly processes interleaved sequences of
speech and text. Utilizing a tokenized early-fusion approach, Ichigo quantizes
speech into discrete tokens and employs a uniform transformer-based
architecture for both speech and text modalities. This method enables joint
reasoning and generation across modalities without the need for separate
adapters. We present a comprehensive training methodology, including
pre-training on multilingual speech recognition datasets and fine-tuning on a
curated instruction dataset. Ichigo demonstrates state-of-the-art performance
on speech question-answering benchmarks, outperforming existing open-source
speech language models and achieving comparable results to cascaded systems.
Notably, Ichigo exhibits a latency of just 111 ms to first token generation,
significantly lower than current models. Our approach not only advances the
field of multimodal AI but also provides a framework for smaller research teams
to contribute effectively to open-source speech-language models.
