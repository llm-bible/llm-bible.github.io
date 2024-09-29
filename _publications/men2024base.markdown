---
layout: publication
title: "Base Of Rope Bounds Context Length"
authors: Men Xin, Xu Mingyu, Wang Bingning, Zhang Qingyu, Lin Hongyu, Han Xianpei, Chen Weipeng
conference: "Arxiv"
year: 2024
bibkey: men2024base
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14591"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Position embedding is a core component of current Large Language Models (LLMs). Rotary position embedding (RoPE) a technique that encodes the position information with a rotation matrix has been the de facto choice for position embedding in many LLMs such as the Llama series. RoPE has been further utilized to extend long context capability which is roughly based on adjusting the (textitbase) parameter of RoPE to mitigate out-of-distribution (OOD) problems in position embedding. However in this paper we find that LLMs may obtain a superficial long-context ability based on the OOD theory. We revisit the role of RoPE in LLMs and propose a novel property of long-term decay we derive that the (textit)base of RoPE bounds context length there is an absolute lower bound for the base value to obtain certain context length capability. Our work reveals the relationship between context length and RoPE base both theoretically and empirically which may shed light on future long context training.
