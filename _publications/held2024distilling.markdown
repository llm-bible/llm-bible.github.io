---
layout: publication
title: 'Distilling An End-to-end Voice Assistant Without Instruction Training Data'
authors: William Held, Ella Li, Michael Ryan, Weiyan Shi, Yanzhe Zhang, Diyi Yang
conference: "Arxiv"
year: 2024
bibkey: held2024distilling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02678'}
tags: ['Fine-Tuning', 'Training Techniques']
---
Voice assistants, such as Siri and Google Assistant, typically model audio
and text separately, resulting in lost speech information and increased
complexity. Recent efforts to address this with end-to-end Speech Large
Language Models (LLMs) trained with supervised finetuning (SFT)
  have led to models ``forgetting" capabilities from text-only LLMs. Our work
proposes an alternative paradigm for training Speech LLMs without instruction
data, using the response of a text-only LLM to transcripts as self-supervision.
Importantly, this process can be performed without annotated responses. We show
that our Distilled Voice Assistant (DiVA) generalizes to Spoken Question
Answering, Classification, and Translation. Furthermore, we show that DiVA
better meets user preferences, achieving a 72% win rate compared with
state-of-the-art models like Qwen 2 Audio, despite using \\(>\\)100x less training
compute.
