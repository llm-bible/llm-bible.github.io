---
layout: publication
title: 'Beyond English: The Impact Of Prompt Translation Strategies Across Languages And Tasks In Multilingual Llms'
authors: Itai Mondshine, Tzuf Paz-argaman, Reut Tsarfaty
conference: "Arxiv"
year: 2025
bibkey: mondshine2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09331"}
tags: ['RAG', 'Prompting', 'Applications']
---
Despite advances in the multilingual capabilities of Large Language Models
(LLMs) across diverse tasks, English remains the dominant language for LLM
research and development. So, when working with a different language, this has
led to the widespread practice of pre-translation, i.e., translating the task
prompt into English before inference. Selective pre-translation, a more
surgical approach, focuses on translating specific prompt components. However,
its current use is sporagic and lacks a systematic research foundation.
Consequently, the optimal pre-translation strategy for various multilingual
settings and tasks remains unclear. In this work, we aim to uncover the optimal
setup for pre-translation by systematically assessing its use. Specifically, we
view the prompt as a modular entity, composed of four functional parts:
instruction, context, examples, and output, either of which could be translated
or not. We evaluate pre-translation strategies across 35 languages covering
both low and high-resource languages, on various tasks including Question
Answering (QA), Natural Language Inference (NLI), Named Entity Recognition
(NER), and Abstractive Summarization. Our experiments show the impact of
factors as similarity to English, translation quality and the size of
pre-trained data, on the model performance with pre-translation. We suggest
practical guidelines for choosing optimal strategies in various multilingual
settings.
