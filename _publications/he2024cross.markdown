---
layout: publication
title: 'Tuba: Cross-lingual Transferability Of Backdoor Attacks In Llms With Instruction Tuning'
authors: Xuanli He, Jun Wang, Qiongkai Xu, Pasquale Minervini, Pontus Stenetorp, Benjamin I. P. Rubinstein, Trevor Cohn
conference: "Arxiv"
year: 2024
bibkey: he2024cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.19597'}
tags: ['RAG', 'Security', 'GPT', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning']
---
The implications of backdoor attacks on English-centric large language models
(LLMs) have been widely examined - such attacks can be achieved by embedding
malicious behaviors during training and activated under specific conditions
that trigger malicious outputs. Despite the increasing support for multilingual
capabilities in open-source and proprietary LLMs, the impact of backdoor
attacks on these systems remains largely under-explored. Our research focuses
on cross-lingual backdoor attacks against multilingual LLMs, particularly
investigating how poisoning the instruction-tuning data for one or two
languages can affect the outputs for languages whose instruction-tuning data
were not poisoned. Despite its simplicity, our empirical analysis reveals that
our method exhibits remarkable efficacy in models like mT5 and GPT-4o, with
high attack success rates, surpassing 90% in more than 7 out of 12 languages
across various scenarios. Our findings also indicate that more powerful models
show increased susceptibility to transferable cross-lingual backdoor attacks,
which also applies to LLMs predominantly pre-trained on English data, such as
Llama2, Llama3, and Gemma. Moreover, our experiments demonstrate 1) High
Transferability: the backdoor mechanism operates successfully in cross-lingual
response scenarios across 26 languages, achieving an average attack success
rate of 99%, and 2) Robustness: the proposed attack remains effective even
after defenses are applied. These findings expose critical security
vulnerabilities in multilingual LLMs and highlight the urgent need for more
robust, targeted defense strategies to address the unique challenges posed by
cross-lingual backdoor transfer.
