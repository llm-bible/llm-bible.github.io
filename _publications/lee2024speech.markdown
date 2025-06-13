---
layout: publication
title: 'Speech-massive: A Multilingual Speech Dataset For SLU And Beyond'
authors: Beomseok Lee, Ioan Calapodescu, Marco Gaido, Matteo Negri, Laurent Besacier
conference: "Arxiv"
year: 2024
bibkey: lee2024speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03900"}
  - {name: "Code", url: "https://github.com/hlt-mt/Speech-MASSIVE"}
tags: ['Model Architecture', 'Training Techniques', 'Has Code', 'Few-Shot', 'Multimodal Models', 'Prompting']
---
We present Speech-MASSIVE, a multilingual Spoken Language Understanding (SLU)
dataset comprising the speech counterpart for a portion of the MASSIVE textual
corpus. Speech-MASSIVE covers 12 languages from different families and inherits
from MASSIVE the annotations for the intent prediction and slot-filling tasks.
Our extension is prompted by the scarcity of massively multilingual SLU
datasets and the growing need for versatile speech datasets to assess
foundation models (LLMs, speech encoders) across languages and tasks. We
provide a multimodal, multitask, multilingual dataset and report SLU baselines
using both cascaded and end-to-end architectures in various training scenarios
(zero-shot, few-shot, and full fine-tune). Furthermore, we demonstrate the
suitability of Speech-MASSIVE for benchmarking other tasks such as speech
transcription, language identification, and speech translation. The dataset,
models, and code are publicly available at:
https://github.com/hlt-mt/Speech-MASSIVE
