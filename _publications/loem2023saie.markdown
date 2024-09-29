---
layout: publication
title: "SAIE Framework: Support Alone Isn't Enough -- Advancing LLM Training With Adversarial Remarks"
authors: Loem Mengsay, Kaneko Masahiro, Okazaki Naoaki
conference: "Arxiv"
year: 2023
bibkey: loem2023saie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08107"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) can justify or critique their predictions through discussions with other models or humans thereby enriching their intrinsic understanding of instances. While proactive discussions in the inference phase have been shown to boost performance such interactions have not been extensively explored during the training phase. We hypothesize that incorporating interactive discussions into the training process can enhance the models understanding and improve their reasoning and verbal expression abilities during inference. This work introduces the SAIE framework which facilitates supportive and adversarial discussions between learner and partner models. The learner model receives responses from the partner and its parameters are then updated based on this discussion. This dynamic adjustment process continues throughout the training phase responding to the evolving outputs of the learner model. Our empirical evaluation across various tasks including math problems commonsense reasoning and multi-domain knowledge demonstrates that models fine-tuned with the SAIE framework outperform those trained with conventional fine-tuning approaches. Furthermore our method enhances the models reasoning capabilities improving both individual and multi-agent inference performance.
