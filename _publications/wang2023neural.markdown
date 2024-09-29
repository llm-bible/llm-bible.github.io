---
layout: publication
title: Neural Codec Language Models Are Zero45;shot Text To Speech Synthesizers
authors: Chengyi Wang, Sanyuan Chen, Yu Wu, Ziqiang Zhang, Long Zhou, Shujie Liu, Zhuo Chen, Yanqing Liu, Huaming Wang, Jinyu Li, Lei He, Sheng Zhao, Furu Wei
conference: "Arxiv"
year: 2023
bibkey: wang2023neural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2301.02111v1"}
  - {name: "Code", url: "https://aka.ms/valle"}
tags: ['Has Code', 'Language Modeling', 'Prompting', 'Training Techniques']
---
We introduce a language modeling approach for text to speech synthesis (TTS). Specifically we train a neural codec language model (called Vall45;E) using discrete codes derived from an off45;the45;shelf neural audio codec model and regard TTS as a conditional language modeling task rather than continuous signal regression as in previous work. During the pre45;training stage we scale up the TTS training data to 60K hours of English speech which is hundreds of times larger than existing systems. Vall45;E emerges in45;context learning capabilities and can be used to synthesize high45;quality personalized speech with only a 345;second enrolled recording of an unseen speaker as an acoustic prompt. Experiment results show that Vall45;E significantly outperforms the state45;of45;the45;art zero45;shot TTS system in terms of speech naturalness and speaker similarity. In addition we find Vall45;E could preserve the speakers emotion and acoustic environment of the acoustic prompt in synthesis. See https://aka.ms/valle for demos of our work.
