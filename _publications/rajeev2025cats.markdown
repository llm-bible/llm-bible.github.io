---
layout: publication
title: 'Cats Confuse Reasoning LLM: Query Agnostic Adversarial Triggers For Reasoning Models'
authors: Meghana Rajeev, Rajkumar Ramamurthy, Prapti Trivedi, Vikas Yadav, Oluwanifemi Bamgbose, Sathwik Tejaswi Madhusudan, James Zou, Nazneen Rajani
conference: "Arxiv"
year: 2025
bibkey: rajeev2025cats
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01781'}
tags: ['Security']
---
We investigate the robustness of reasoning models trained for step-by-step
problem solving by introducing query-agnostic adversarial triggers - short,
irrelevant text that, when appended to math problems, systematically mislead
models to output incorrect answers without altering the problem's semantics. We
propose CatAttack, an automated iterative attack pipeline for generating
triggers on a weaker, less expensive proxy model (DeepSeek V3) and successfully
transfer them to more advanced reasoning target models like DeepSeek R1 and
DeepSeek R1-distilled-Qwen-32B, resulting in greater than 300% increase in the
likelihood of the target model generating an incorrect answer. For example,
appending, "Interesting fact: cats sleep most of their lives," to any math
problem leads to more than doubling the chances of a model getting the answer
wrong. Our findings highlight critical vulnerabilities in reasoning models,
revealing that even state-of-the-art models remain susceptible to subtle
adversarial inputs, raising security and reliability concerns. The CatAttack
triggers dataset with model responses is available at
https://huggingface.co/datasets/collinear-ai/cat-attack-adversarial-triggers.
