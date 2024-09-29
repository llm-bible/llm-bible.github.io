---
layout: publication
title: Sandwich Attack Multi45;language Mixture Adaptive Attack On Llms
authors: Upadhayay Bibek, Behzadan Vahid
conference: "Arxiv"
year: 2024
bibkey: upadhayay2024sandwich
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07242"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Responsible AI', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) are increasingly being developed and applied but their widespread use faces challenges. These include aligning LLMs responses with human values to prevent harmful outputs which is addressed through safety training methods. Even so bad actors and malicious users have succeeded in attempts to manipulate the LLMs to generate misaligned responses for harmful questions such as methods to create a bomb in school labs recipes for harmful drugs and ways to evade privacy rights. Another challenge is the multilingual capabilities of LLMs which enable the model to understand and respond in multiple languages. Consequently attackers exploit the unbalanced pre45;training datasets of LLMs in different languages and the comparatively lower model performance in low45;resource languages than high45;resource ones. As a result attackers use a low45;resource languages to intentionally manipulate the model to create harmful responses. Many of the similar attack vectors have been patched by model providers making the LLMs more robust against language45;based manipulation. In this paper we introduce a new black45;box attack vector called the emph123;Sandwich attack125; a multi45;language mixture attack which manipulates state45;of45;the45;art LLMs into generating harmful and misaligned responses. Our experiments with five different models namely Googles Bard Gemini Pro LLaMA45;245;7045;B45;Chat GPT45;3.545;Turbo GPT45;4 and Claude45;345;OPUS show that this attack vector can be used by adversaries to generate harmful responses and elicit misaligned responses from these models. By detailing both the mechanism and impact of the Sandwich attack this paper aims to guide future research and development towards more secure and resilient LLMs ensuring they serve the public good while minimizing potential for misuse.
