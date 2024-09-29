---
layout: publication
title: M45;adapter Modality Adaptation For End45;to45;end Speech45;to45;text Translation
authors: Zhao Jinming, Yang Hao, Shareghi Ehsan, Haffari Gholamreza
conference: "Arxiv"
year: 2022
bibkey: zhao2022m
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.00952"}
  - {name: "Code", url: "https://github.com/mingzi151/w2v2&#45;st.&#125;"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
End45;to45;end speech45;to45;text translation models are often initialized with pre45;trained speech encoder and pre45;trained text decoder. This leads to a significant training gap between pre45;training and fine45;tuning largely due to the modality differences between speech outputs from the encoder and text inputs to the decoder. In this work we aim to bridge the modality gap between speech and text to improve translation quality. We propose M45;Adapter a novel Transformer45;based module to adapt speech representations to text. While shrinking the speech sequence M45;Adapter produces features desired for speech45;to45;text translation via modelling global and local dependencies of a speech sequence. Our experimental results show that our model outperforms a strong baseline by up to 1 BLEU score on the Must45;C En→DE dataset.footnote123;Our code is available at https://github.com/mingzi151/w2v2&#45;st.&#125;
