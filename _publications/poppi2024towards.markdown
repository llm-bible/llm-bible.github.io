---
layout: publication
title: 'Towards Understanding The Fragility Of Multilingual Llms Against Fine-tuning Attacks'
authors: Samuele Poppi, Zheng-xin Yong, Yifei He, Bobbie Chern, Han Zhao, Aobo Yang, Jianfeng Chi
conference: "Arxiv"
year: 2024
bibkey: poppi2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18210'}
tags: ['RAG', 'Security', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Recent advancements in Large Language Models (LLMs) have sparked widespread
concerns about their safety. Recent work demonstrates that safety alignment of
LLMs can be easily removed by fine-tuning with a few adversarially chosen
instruction-following examples, i.e., fine-tuning attacks. We take a further
step to understand fine-tuning attacks in multilingual LLMs. We first discover
cross-lingual generalization of fine-tuning attacks: using a few adversarially
chosen instruction-following examples in one language, multilingual LLMs can
also be easily compromised (e.g., multilingual LLMs fail to refuse harmful
prompts in other languages). Motivated by this finding, we hypothesize that
safety-related information is language-agnostic and propose a new method termed
Safety Information Localization (SIL) to identify the safety-related
information in the model parameter space. Through SIL, we validate this
hypothesis and find that only changing 20% of weight parameters in fine-tuning
attacks can break safety alignment across all languages. Furthermore, we
provide evidence to the alternative pathways hypothesis for why freezing
safety-related parameters does not prevent fine-tuning attacks, and we
demonstrate that our attack vector can still jailbreak LLMs adapted to new
languages.
