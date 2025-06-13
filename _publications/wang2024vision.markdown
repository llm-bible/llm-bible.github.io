---
layout: publication
title: 'Vision-and-language Navigation Via Causal Learning'
authors: Liuyi Wang, Zongtao He, Ronghao Dang, Mengjiao Shen, Chengju Liu, Qijun Chen
conference: "Arxiv"
year: 2024
bibkey: wang2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10241"}
  - {name: "Code", url: "https://github.com/CrystalSixone/VLN-GOAT"}
tags: ['Transformer', 'Pre-Training', 'Agentic', 'Ethics and Bias', 'Model Architecture', 'ACL', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
In the pursuit of robust and generalizable environment perception and
language understanding, the ubiquitous challenge of dataset bias continues to
plague vision-and-language navigation (VLN) agents, hindering their performance
in unseen environments. This paper introduces the generalized cross-modal
causal transformer (GOAT), a pioneering solution rooted in the paradigm of
causal inference. By delving into both observable and unobservable confounders
within vision, language, and history, we propose the back-door and front-door
adjustment causal learning (BACL and FACL) modules to promote unbiased learning
by comprehensively mitigating potential spurious correlations. Additionally, to
capture global confounder features, we propose a cross-modal feature pooling
(CFP) module supervised by contrastive learning, which is also shown to be
effective in improving cross-modal representations during pre-training.
Extensive experiments across multiple VLN datasets (R2R, REVERIE, RxR, and
SOON) underscore the superiority of our proposed method over previous
state-of-the-art approaches. Code is available at
https://github.com/CrystalSixone/VLN-GOAT.
