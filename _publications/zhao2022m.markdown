---
layout: publication
title: M-adapter: Modality Adaptation For End-to-end Speech-to-text Translation
authors: Zhao Jinming, Yang Hao, Shareghi Ehsan, Haffari Gholamreza
conference: "Arxiv"
year: 2022
bibkey: zhao2022m
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.00952"}
  - {name: "Code", url: "https://github.com/mingzi151/w2v2-st."}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
End-to-end speech-to-text translation models are often initialized with pre-trained speech encoder and pre-trained text decoder. This leads to a significant training gap between pre-training and fine-tuning largely due to the modality differences between speech outputs from the encoder and text inputs to the decoder. In this work we aim to bridge the modality gap between speech and text to improve translation quality. We propose M-Adapter a novel Transformer-based module to adapt speech representations to text. While shrinking the speech sequence M-Adapter produces features desired for speech-to-text translation via modelling global and local dependencies of a speech sequence. Our experimental results show that our model outperforms a strong baseline by up to 1 BLEU score on the Must-C En(rightarrow)DE dataset.(footnote)Our code is available at https://github.com/mingzi151/w2v2-st.\}"
