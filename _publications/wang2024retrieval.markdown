---
layout: publication
title: Retrieval Augmented End-to-end Spoken Dialog Models
authors: Wang Mingqiu, Shafran Izhak, Soltau Hagen, Han Wei, Cao Yuan, Yu Dian, Shafey Laurent El
conference: "Proc. ICASSP"
year: 2024
bibkey: wang2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01828"}
tags: ['Applications', 'Ethics And Bias', 'In Context Learning', 'Prompting', 'RAG', 'Reinforcement Learning']
---
We recently developed SLM a joint speech and language model which fuses a pretrained foundational speech model and a large language model (LLM) while preserving the in-context learning capability intrinsic to the pretrained LLM. In this paper we apply SLM to speech dialog applications where the dialog states are inferred directly from the audio signal. Task-oriented dialogs often contain domain-specific entities i.e. restaurants hotels train stations and city names which are difficult to recognize however critical for the downstream applications. Inspired by the RAG (retrieval-augmented generation) paradigm we propose a retrieval augmented SLM (ReSLM) that overcomes this weakness. We first train a speech retriever to retrieve text entities mentioned in the audio. The retrieved entities are then added as text inputs to the underlying SLM to bias model predictions. We evaluated ReSLM on speech MultiWoz task (DSTC-11 challenge) and found that this retrieval augmentation boosts model performance achieving joint goal accuracy (38.637; vs 32.737;) slot error rate (20.637; vs 24.837;) and ASR word error rate (5.537; vs 6.737;). While demonstrated on dialog state tracking our approach is broadly applicable to other speech tasks requiring contextual information or domain-specific entities such as contextual ASR with biasing capability.
