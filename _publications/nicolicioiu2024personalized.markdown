---
layout: publication
title: Panza\: A Personalized Text Writing Assistant Via Data Playback And Local Fine-tuning
authors: Nicolicioiu Armand, Iofinova Eugenia, Kurtic Eldar, Nikdan Mahdi, Panferov Andrei, Markov Ilia, Shavit Nir, Alistarh Dan
conference: "Arxiv"
year: 2024
bibkey: nicolicioiu2024personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10994"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
The availability of powerful open-source large language models (LLMs) opens exciting use-cases such as automated personal assistants that adapt to the users unique data and demands. Two key desiderata for such assistants are personalization-in the sense that the assistant should reflect the users own style-and privacy-in the sense that users may prefer to always store their personal data locally on their own computing device. We present a new design for such an automated assistant for the specific use case of personal assistant for email generation which we call Panza. Specifically Panza can be both trained and inferenced locally on commodity hardware and is personalized to the users writing style. Panzas personalization features are based on a new technique called data playback which allows us to fine-tune an LLM to better reflect a users writing style using limited data. We show that by combining efficient fine-tuning and inference methods Panza can be executed entirely locally using limited resources-specifically it can be executed within the same resources as a free Google Colab instance. Finally our key methodological contribution is a careful study of evaluation metrics and of how different choices of system components (e.g. the use of Retrieval-Augmented Generation or different fine-tuning approaches) impact the systems performance.
