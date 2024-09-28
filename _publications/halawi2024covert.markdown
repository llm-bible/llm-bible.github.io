---
layout: publication
title: Covert Malicious Finetuning Challenges in Safeguarding LLM Adaptation
authors: Halawi Danny, Wei Alexander, Wallace Eric, Wang Tony T., Haghtalab Nika, Steinhardt Jacob
conference: "Arxiv"
year: 2024
bibkey: halawi2024covert
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20053"}
tags: ['ARXIV', 'GPT', 'LLM', 'Merging', 'Pretraining Methods']
---
Black-box finetuning is an emerging interface for adapting state-of-the-art language models to user needs. However such access may also let malicious actors undermine model safety. To demonstrate the challenge of defending finetuning interfaces we introduce covert malicious finetuning a method to compromise model safety via finetuning while evading detection. Our method constructs a malicious dataset where every individual datapoint appears innocuous but finetuning on the dataset teaches the model to respond to encoded harmful requests with encoded harmful responses. Applied to GPT-4 our method produces a finetuned model that acts on harmful instructions 99 of the time and avoids detection by defense mechanisms such as dataset inspection safety evaluations and input/output classifiers. Our findings question whether black-box finetuning access can be secured against sophisticated adversaries.
