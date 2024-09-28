---
layout: publication
title: LLM Lies Hallucinations are not Bugs but Features as Adversarial Examples
authors: Yao Jia-yu, Ning Kun-peng, Liu Zhen-hui, Ning Mu-nan, Liu Yu-yang, Yuan Li
conference: "Arxiv"
year: 2023
bibkey: yao2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01469"}
  - {name: "Code", url: "https://github.com/PKU-YuanGroup/Hallucination-Attack}"}
tags: ['ARXIV', 'GPT', 'Has Code', 'LLM', 'Model Architecture', 'Prompt', 'Security', 'Transformer']
---
Large Language Models (LLMs) including GPT-3.5 LLaMA and PaLM seem to be knowledgeable and able to adapt to many tasks. However we still cannot completely trust their answers since LLMs suffer from textemdash fabricating non-existent facts deceiving users with or without their awareness. However the reasons for their existence and pervasiveness remain unclear. In this paper we demonstrate that nonsensical prompts composed of random tokens can also elicit the LLMs to respond with hallucinations. Moreover we provide both theoretical and experimental evidence that transformers can be manipulated to produce specific pre-define tokens by perturbing its input sequence. This phenomenon forces us to revisit that and it shares similar characteristics with conventional adversarial examples as a basic property of LLMs. Therefore we formalize an automatic hallucination triggering method as the in an adversarial way. Finally we explore the basic properties of attacked adversarial prompts and propose a simple yet effective defense strategy. Our code is released on GitHubfootnotehttps://github.com/PKU-YuanGroup/Hallucination-Attack}.
