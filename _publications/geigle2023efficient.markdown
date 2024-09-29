---
layout: publication
title: Mblip&#58; Efficient Bootstrapping Of Multilingual Vision-llms
authors: Geigle Gregor, Jain Abhay, Timofte Radu, Glavaš Goran
conference: "Arxiv"
year: 2023
bibkey: geigle2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.06930"}
  - {name: "Code", url: "https://github.com/gregor-ge/mBLIP"}
tags: ['Has Code', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Modular vision-language models (Vision-LLMs) align pretrained image encoders with (frozen) large language models (LLMs) and post-hoc condition LLMs to understand the image input. With the abundance of readily available high-quality English image-text data as well as strong monolingual English LLMs the research focus has been on English-only Vision-LLMs. Multilingual vision-language models are still predominantly obtained via expensive end-to-end pretraining resulting in comparatively smaller models trained on limited multilingual image data supplemented with text-only multilingual corpora. We present mBLIP the first Vision-LLM leveraging multilingual LLMs which we obtain in a computationally efficient manner on consumer-level hardware. To this end we (textit)re-align an image encoder previously tuned to an English LLM to a new multilingual LLM using only a few million multilingual training examples derived from a mix of vision-and-language tasks which we obtain by machine-translating high-quality English data to 95 languages. On the IGLUE benchmark and XM3600 mBLIP yields results competitive with state-of-the-art models and it greatly outperforms strong English-only Vision-LLMs like Llava 1.5. We release our model code and train data at (url)https://github.com/gregor-ge/mBLIP\}."
