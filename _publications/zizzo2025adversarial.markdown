---
layout: publication
title: 'Adversarial Prompt Evaluation: Systematic Benchmarking Of Guardrails Against Prompt Input Attacks On Llms'
authors: Giulio Zizzo, Giandomenico Cornacchia, Kieran Fraser, Muhammad Zaid Hameed, Ambrish Rawat, Beat Buesser, Mark Purcell, Pin-yu Chen, Prasanna Sattigeri, Kush Varshney
conference: "Arxiv"
year: 2025
bibkey: zizzo2025adversarial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15427'}
  - {name: "Code", url: 'https://github.com/IBM/Adversarial-Prompt-Evaluation'}
tags: ['Prompting', 'Has Code', 'Security', 'Applications']
---
As large language models (LLMs) become integrated into everyday applications,
ensuring their robustness and security is increasingly critical. In particular,
LLMs can be manipulated into unsafe behaviour by prompts known as jailbreaks.
The variety of jailbreak styles is growing, necessitating the use of external
defences known as guardrails. While many jailbreak defences have been proposed,
not all defences are able to handle new out-of-distribution attacks due to the
narrow segment of jailbreaks used to align them. Moreover, the lack of
systematisation around defences has created significant gaps in their practical
application. In this work, we perform systematic benchmarking across 15
different defences, considering a broad swathe of malicious and benign
datasets. We find that there is significant performance variation depending on
the style of jailbreak a defence is subject to. Additionally, we show that
based on current datasets available for evaluation, simple baselines can
display competitive out-of-distribution performance compared to many
state-of-the-art defences. Code is available at
https://github.com/IBM/Adversarial-Prompt-Evaluation.
