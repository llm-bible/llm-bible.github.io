---
layout: publication
title: 'Internalizing ASR With Implicit Chain Of Thought For Efficient Speech-to-speech Conversational LLM'
authors: Robin Shing-hei Yuen, Timothy Tin-long Tse, Jian Zhu
conference: "Arxiv"
year: 2024
bibkey: yuen2024internalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17353"}
tags: ['Uncategorized']
---
Current speech-based LLMs are predominantly trained on extensive ASR and TTS
datasets, excelling in tasks related to these domains. However, their ability
to handle direct speech-to-speech conversations remains notably constrained.
These models often rely on an ASR-to-TTS chain-of-thought pipeline, converting
speech into text for processing before generating audio responses, which
introduces latency and loses audio features. We propose a method that
implicitly internalizes ASR chain of thought into a speech LLM, enhancing its
native speech understanding capabilities. Our approach reduces latency and
improves the model's native understanding of speech, paving the way for more
efficient and natural real-time audio interactions. We also release a
large-scale synthetic conversational dataset to facilitate further research.
