---
layout: publication
title: "Large Language Models Are Involuntary Truth-tellers: Exploiting Fallacy Failure For Jailbreak Attacks"
authors: Zhou Yue, Zou Henry Peng, Di Eugenio Barbara, Zhang Yang
conference: "Arxiv"
year: 2024
bibkey: zhou2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00869"}
tags: ['Pretraining Methods', 'Responsible AI', 'Security']
---
We find that language models have difficulties generating fallacious and deceptive reasoning. When asked to generate deceptive outputs language models tend to leak honest counterparts but believe them to be false. Exploiting this deficiency we propose a jailbreak attack method that elicits an aligned language model for malicious output. Specifically we query the model to generate a fallacious yet deceptively real procedure for the harmful behavior. Since a fallacious procedure is generally considered fake and thus harmless by LLMs it helps bypass the safeguard mechanism. Yet the output is factually harmful since the LLM cannot fabricate fallacious solutions but proposes truthful ones. We evaluate our approach over five safety-aligned large language models comparing four previous jailbreak methods and show that our approach achieves competitive performance with more harmful outputs. We believe the findings could be extended beyond model safety such as self-verification and hallucination.
