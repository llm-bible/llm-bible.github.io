---
layout: publication
title: Mblip Efficient Bootstrapping Of Multilingual Vision45;llms
authors: Geigle Gregor, Jain Abhay, Timofte Radu, Glavaš Goran
conference: "Arxiv"
year: 2023
bibkey: geigle2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.06930"}
  - {name: "Code", url: "https://github.com/gregor&#45;ge/mBLIP&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Modular vision45;language models (Vision45;LLMs) align pretrained image encoders with (frozen) large language models (LLMs) and post45;hoc condition LLMs to understand the image input. With the abundance of readily available high45;quality English image45;text data as well as strong monolingual English LLMs the research focus has been on English45;only Vision45;LLMs. Multilingual vision45;language models are still predominantly obtained via expensive end45;to45;end pretraining resulting in comparatively smaller models trained on limited multilingual image data supplemented with text45;only multilingual corpora. We present mBLIP the first Vision45;LLM leveraging multilingual LLMs which we obtain in a computationally efficient manner on consumer45;level hardware. To this end we textit123;re45;align125; an image encoder previously tuned to an English LLM to a new multilingual LLM using only a few million multilingual training examples derived from a mix of vision45;and45;language tasks which we obtain by machine45;translating high45;quality English data to 95 languages. On the IGLUE benchmark and XM3600 mBLIP yields results competitive with state45;of45;the45;art models and it greatly outperforms strong English45;only Vision45;LLMs like Llava 1.5. We release our model code and train data at url123;https://github.com/gregor&#45;ge/mBLIP&#125;.
