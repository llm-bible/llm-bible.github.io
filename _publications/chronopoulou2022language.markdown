---
layout: publication
title: Language45;family Adapters For Low45;resource Multilingual Neural Machine Translation
authors: Chronopoulou Alexandra, Stojanovski Dario, Fraser Alexander
conference: "Arxiv"
year: 2022
bibkey: chronopoulou2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.15236"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large multilingual models trained with self45;supervision achieve state45;of45;the45;art results in a wide range of natural language processing tasks. Self45;supervised pretrained models are often fine45;tuned on parallel data from one or multiple language pairs for machine translation. Multilingual fine45;tuning improves performance on low45;resource languages but requires modifying the entire model and can be prohibitively expensive. Training a new adapter on each language pair or training a single adapter on all language pairs without updating the pretrained model has been proposed as a parameter45;efficient alternative. However the former does not permit any sharing between languages while the latter shares parameters for all languages and is susceptible to negative interference. In this paper we propose training language45;family adapters on top of mBART45;50 to facilitate cross45;lingual transfer. Our approach outperforms related baselines yielding higher translation scores on average when translating from English to 17 different low45;resource languages. We also show that language45;family adapters provide an effective method to translate to languages unseen during pretraining.
