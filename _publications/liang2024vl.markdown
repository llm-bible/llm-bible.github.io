---
layout: publication
title: Vl45;trojan Multimodal Instruction Backdoor Attacks Against Autoregressive Visual Language Models
authors: Liang Jiawei, Liang Siyuan, Luo Man, Liu Aishan, Han Dongchen, Chang Ee-chien, Cao Xiaochun
conference: "Arxiv"
year: 2024
bibkey: liang2024vl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13851"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Security']
---
Autoregressive Visual Language Models (VLMs) showcase impressive few45;shot learning capabilities in a multimodal context. Recently multimodal instruction tuning has been proposed to further enhance instruction45;following abilities. However we uncover the potential threat posed by backdoor attacks on autoregressive VLMs during instruction tuning. Adversaries can implant a backdoor by injecting poisoned samples with triggers embedded in instructions or images enabling malicious manipulation of the victim models predictions with predefined triggers. Nevertheless the frozen visual encoder in autoregressive VLMs imposes constraints on the learning of conventional image triggers. Additionally adversaries may encounter restrictions in accessing the parameters and architectures of the victim model. To address these challenges we propose a multimodal instruction backdoor attack namely VL45;Trojan. Our approach facilitates image trigger learning through an isolating and clustering strategy and enhance black45;box45;attack efficacy via an iterative character45;level text trigger generation method. Our attack successfully induces target outputs during inference significantly surpassing baselines (+62.5237;) in ASR. Moreover it demonstrates robustness across various model scales and few45;shot in45;context reasoning scenarios.
