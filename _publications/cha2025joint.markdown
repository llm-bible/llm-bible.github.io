---
layout: publication
title: 'JELLY: Joint Emotion Recognition And Context Reasoning With Llms For Conversational Speech Synthesis'
authors: Jun-hyeok Cha, Seung-bin Kim, Hyung-seok Oh, Seong-whan Lee
conference: "Arxiv"
year: 2025
bibkey: cha2025joint
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04904'}
tags: ['Training Techniques', 'Fine-Tuning', 'Tools', 'Pretraining Methods']
---
Recently, there has been a growing demand for conversational speech synthesis
(CSS) that generates more natural speech by considering the conversational
context. To address this, we introduce JELLY, a novel CSS framework that
integrates emotion recognition and context reasoning for generating appropriate
speech in conversation by fine-tuning a large language model (LLM) with
multiple partial LoRA modules. We propose an Emotion-aware Q-former encoder,
which enables the LLM to perceive emotions in speech. The encoder is trained to
align speech emotions with text, utilizing datasets of emotional speech. The
entire model is then fine-tuned with conversational speech data to infer
emotional context for generating emotionally appropriate speech in
conversation. Our experimental results demonstrate that JELLY excels in
emotional context modeling, synthesizing speech that naturally aligns with
conversation, while mitigating the scarcity of emotional conversational speech
datasets.
