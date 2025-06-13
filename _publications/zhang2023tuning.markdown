---
layout: publication
title: 'Tuning Large Language Model For End-to-end Speech Translation'
authors: Hao Zhang, Nianwen Si, Yaqi Chen, Wenlin Zhang, Xukui Yang, Dan Qu, Xiaolin Jiao
conference: "Arxiv"
year: 2023
bibkey: zhang2023tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02050"}
tags: ['Fine-Tuning', 'GPT', 'Survey Paper', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
With the emergence of large language models (LLMs), multimodal models based
on LLMs have demonstrated significant potential. Models such as LLaSM, X-LLM,
and SpeechGPT exhibit an impressive ability to comprehend and generate human
instructions. However, their performance often falters when faced with complex
tasks like end-to-end speech translation (E2E-ST), a cross-language and
cross-modal translation task. In comparison to single-modal models, multimodal
models lag behind in these scenarios. This paper introduces LST, a Large
multimodal model designed to excel at the E2E-ST task. LST consists of a speech
frontend, an adapter, and a LLM backend. The training of LST consists of two
stages: (1) Modality adjustment, where the adapter is tuned to align speech
representation with text embedding space, and (2) Downstream task fine-tuning,
where both the adapter and LLM model are trained to optimize performance on the
E2EST task. Experimental results on the MuST-C speech translation benchmark
demonstrate that LST-13B achieves BLEU scores of 30.39/41.55/35.33 on
En-De/En-Fr/En-Es language pairs, surpassing previous models and establishing a
new state-of-the-art. Additionally, we conduct an in-depth analysis of
single-modal model selection and the impact of training strategies, which lays
the foundation for future research. We will open up our code and models after
review.
