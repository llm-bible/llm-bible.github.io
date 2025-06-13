---
layout: publication
title: 'Do Multilingual Llms Think In English?'
authors: Lisa Schut, Yarin Gal, Sebastian Farquhar
conference: "Arxiv"
year: 2025
bibkey: schut2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15603'}
tags: ['Uncategorized']
---
Large language models (LLMs) have multilingual capabilities and can solve
tasks across various languages. However, we show that current LLMs make key
decisions in a representation space closest to English, regardless of their
input and output languages. Exploring the internal representations with a logit
lens for sentences in French, German, Dutch, and Mandarin, we show that the LLM
first emits representations close to English for semantically-loaded words
before translating them into the target language. We further show that
activation steering in these LLMs is more effective when the steering vectors
are computed in English rather than in the language of the inputs and outputs.
This suggests that multilingual LLMs perform key reasoning steps in a
representation that is heavily shaped by English in a way that is not
transparent to system users.
