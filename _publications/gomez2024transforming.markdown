---
layout: publication
title: Transforming Llms Into Cross45;modal And Cross45;lingual Retrieval Systems
authors: Gomez Frank Palma, Sanabria Ramon, Sung Yun-hsuan, Cer Daniel, Dalmia Siddharth, Abrego Gustavo Hernandez
conference: "Arxiv"
year: 2024
bibkey: gomez2024transforming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01616"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
Large language models (LLMs) are trained on text45;only data that go far beyond the languages with paired speech and text data. At the same time Dual Encoder (DE) based retrieval systems project queries and documents into the same embedding space and have demonstrated their success in retrieval and bi45;text mining. To match speech and text in many languages we propose using LLMs to initialize multi45;modal DE retrieval systems. Unlike traditional methods our system doesnt require speech data during LLM pre45;training and can exploit LLMs multilingual text understanding capabilities to match speech and text in languages unseen during retrieval training. Our multi45;modal LLM45;based retrieval system is capable of matching speech and text in 102 languages despite only training on 21 languages. Our system outperforms previous systems trained explicitly on all 102 languages. We achieve a 1037; absolute improvement in Recall35;64;1 averaged across these languages. Additionally our model demonstrates cross45;lingual speech and text matching which is further enhanced by readily available machine translation data.
