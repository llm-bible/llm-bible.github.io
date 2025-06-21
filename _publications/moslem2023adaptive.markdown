---
layout: publication
title: Adaptive Machine Translation With Large Language Models
authors: Yasmin Moslem, Rejwanul Haque, John D. Kelleher, Andy Way
conference: Arxiv
year: 2023
citations: 28
bibkey: moslem2023adaptive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.13294'}]
tags: [Fine-Tuning, Few-Shot, In-Context Learning, Prompting, Language Modeling]
---
Consistency is a key requirement of high-quality translation. It is
especially important to adhere to pre-approved terminology and adapt to
corrected translations in domain-specific projects. Machine translation (MT)
has achieved significant progress in the area of domain adaptation. However,
real-time adaptation remains challenging. Large-scale language models (LLMs)
have recently shown interesting capabilities of in-context learning, where they
learn to replicate certain input-output text generation patterns, without
further fine-tuning. By feeding an LLM at inference time with a prompt that
consists of a list of translation pairs, it can then simulate the domain and
style characteristics. This work aims to investigate how we can utilize
in-context learning to improve real-time adaptive MT. Our extensive experiments
show promising results at translation time. For example, LLMs can adapt to a
set of in-domain sentence pairs and/or terminology while translating a new
sentence. We observe that the translation quality with few-shot in-context
learning can surpass that of strong encoder-decoder MT systems, especially for
high-resource languages. Moreover, we investigate whether we can combine MT
from strong encoder-decoder models with fuzzy matches, which can further
improve translation quality, especially for less supported languages. We
conduct our experiments across five diverse language pairs, namely
English-to-Arabic (EN-AR), English-to-Chinese (EN-ZH), English-to-French
(EN-FR), English-to-Kinyarwanda (EN-RW), and English-to-Spanish (EN-ES).