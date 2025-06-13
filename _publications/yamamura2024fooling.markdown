---
layout: publication
title: 'Fooling LLM Graders Into Giving Better Grades Through Neural Activity Guided Adversarial Prompting'
authors: Atsushi Yamamura, Surya Ganguli
conference: "Arxiv"
year: 2024
bibkey: yamamura2024fooling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15275"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
The deployment of artificial intelligence (AI) in critical decision-making
and evaluation processes raises concerns about inherent biases that malicious
actors could exploit to distort decision outcomes. We propose a systematic
method to reveal such biases in AI evaluation systems and apply it to automated
essay grading as an example. Our approach first identifies hidden neural
activity patterns that predict distorted decision outcomes and then optimizes
an adversarial input suffix to amplify such patterns. We demonstrate that this
combination can effectively fool large language model (LLM) graders into
assigning much higher grades than humans would. We further show that this
white-box attack transfers to black-box attacks on other models, including
commercial closed-source models like Gemini. They further reveal the existence
of a "magic word" that plays a pivotal role in the efficacy of the attack. We
trace the origin of this magic word bias to the structure of commonly-used chat
templates for supervised fine-tuning of LLMs and show that a minor change in
the template can drastically reduce the bias. This work not only uncovers
vulnerabilities in current LLMs but also proposes a systematic method to
identify and remove hidden biases, contributing to the goal of ensuring AI
safety and security.
