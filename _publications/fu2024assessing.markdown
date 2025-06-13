---
layout: publication
title: 'Poisonbench: Assessing Large Language Model Vulnerability To Data Poisoning'
authors: Tingchen Fu, Mrinank Sharma, Philip Torr, Shay B. Cohen, David Krueger, Fazl Barez
conference: "Arxiv"
year: 2024
bibkey: fu2024assessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.08811'}
tags: ['Ethics and Bias', 'Security']
---
Preference learning is a central component for aligning current LLMs, but
this process can be vulnerable to data poisoning attacks. To address this
concern, we introduce PoisonBench, a benchmark for evaluating large language
models' susceptibility to data poisoning during preference learning. Data
poisoning attacks can manipulate large language model responses to include
hidden malicious content or biases, potentially causing the model to generate
harmful or unintended outputs while appearing to function normally. We deploy
two distinct attack types across eight realistic scenarios, assessing 21
widely-used models. Our findings reveal concerning trends: (1) Scaling up
parameter size does not inherently enhance resilience against poisoning
attacks; (2) There exists a log-linear relationship between the effects of the
attack and the data poison ratio; (3) The effect of data poisoning can
generalize to extrapolated triggers that are not included in the poisoned data.
These results expose weaknesses in current preference learning techniques,
highlighting the urgent need for more robust defenses against malicious models
and data manipulation.
