---
layout: publication
title: 'Finetuning-activated Backdoors In Llms'
authors: Thibaud Gloaguen, Mark Vero, Robin Staab, Martin Vechev
conference: "Arxiv"
year: 2025
bibkey: gloaguen2025finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16567"}
tags: ['Security', 'Training Techniques']
---
Finetuning openly accessible Large Language Models (LLMs) has become standard practice for achieving task-specific performance improvements. Until now, finetuning has been regarded as a controlled and secure process in which training on benign datasets led to predictable behaviors. In this paper, we demonstrate for the first time that an adversary can create poisoned LLMs that initially appear benign but exhibit malicious behaviors once finetuned by downstream users. To this end, our proposed attack, FAB (Finetuning-Activated Backdoor), poisons an LLM via meta-learning techniques to simulate downstream finetuning, explicitly optimizing for the emergence of malicious behaviors in the finetuned models. At the same time, the poisoned LLM is regularized to retain general capabilities and to exhibit no malicious behaviors prior to finetuning. As a result, when users finetune the seemingly benign model on their own datasets, they unknowingly trigger its hidden backdoor behavior. We demonstrate the effectiveness of FAB across multiple LLMs and three target behaviors: unsolicited advertising, refusal, and jailbreakability. Additionally, we show that FAB-backdoors are robust to various finetuning choices made by the user (e.g., dataset, number of steps, scheduler). Our findings challenge prevailing assumptions about the security of finetuning, revealing yet another critical attack vector exploiting the complexities of LLMs.
