---
layout: publication
title: Tuning Large Language Model For End45;to45;end Speech Translation
authors: Zhang Hao, Si Nianwen, Chen Yaqi, Zhang Wenlin, Yang Xukui, Qu Dan, Jiao Xiaolin
conference: "Arxiv"
year: 2023
bibkey: zhang2023tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02050"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Survey Paper', 'Training Techniques']
---
With the emergence of large language models (LLMs) multimodal models based on LLMs have demonstrated significant potential. Models such as LLaSM X45;LLM and SpeechGPT exhibit an impressive ability to comprehend and generate human instructions. However their performance often falters when faced with complex tasks like end45;to45;end speech translation (E2E45;ST) a cross45;language and cross45;modal translation task. In comparison to single45;modal models multimodal models lag behind in these scenarios. This paper introduces LST a Large multimodal model designed to excel at the E2E45;ST task. LST consists of a speech frontend an adapter and a LLM backend. The training of LST consists of two stages (1) Modality adjustment where the adapter is tuned to align speech representation with text embedding space and (2) Downstream task fine45;tuning where both the adapter and LLM model are trained to optimize performance on the E2EST task. Experimental results on the MuST45;C speech translation benchmark demonstrate that LST45;13B achieves BLEU scores of 30.39/41.55/35.33 on En45;De/En45;Fr/En45;Es language pairs surpassing previous models and establishing a new state45;of45;the45;art. Additionally we conduct an in45;depth analysis of single45;modal model selection and the impact of training strategies which lays the foundation for future research. We will open up our code and models after review.
