---
layout: publication
title: Multimodal Dialog Systems With Dual Knowledge-enhanced Generative Pretrained Language Model
authors: Chen Xiaolin, Song Xuemeng, Jing Liqiang, Li Shuo, Hu Linmei, Nie Liqiang
conference: "Arxiv"
year: 2022
bibkey: chen2022multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.07934"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Text response generation for multimodal task-oriented dialog systems which aims to generate the proper text response given the multimodal context is an essential yet challenging task. Although existing efforts have achieved compelling success they still suffer from two pivotal limitations 1) overlook the benefit of generative pre-training and 2) ignore the textual context related knowledge. To address these limitations we propose a novel dual knowledge-enhanced generative pretrained language model for multimodal task-oriented dialog systems (DKMD) consisting of three key components dual knowledge selection dual knowledge-enhanced context learning and knowledge-enhanced response generation. To be specific the dual knowledge selection component aims to select the related knowledge according to both textual and visual modalities of the given context. Thereafter the dual knowledge-enhanced context learning component targets seamlessly integrating the selected knowledge into the multimodal context learning from both global and local perspectives where the cross-modal semantic relation is also explored. Moreover the knowledge-enhanced response generation component comprises a revised BART decoder where an additional dot-product knowledge-decoder attention sub-layer is introduced for explicitly utilizing the knowledge to advance the text response generation. Extensive experiments on a public dataset verify the superiority of the proposed DKMD over state-of-the-art competitors.
