---
layout: publication
title: 'Neutralizing Backdoors Through Information Conflicts For Large Language Models'
authors: Chen Chen, Yuchen Sun, Xueluan Gong, Jiaxin Gao, Kwok-yan Lam
conference: "Arxiv"
year: 2024
bibkey: chen2024neutralizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.18280'}
tags: ['RAG', 'Prompting', 'Security']
---
Large language models (LLMs) have seen significant advancements, achieving
superior performance in various Natural Language Processing (NLP) tasks, from
understanding to reasoning. However, they remain vulnerable to backdoor
attacks, where models behave normally for standard queries but generate harmful
responses or unintended output when specific triggers are activated. Existing
backdoor defenses often suffer from drawbacks that they either focus on
detection without removal, rely on rigid assumptions about trigger properties,
or prove to be ineffective against advanced attacks like multi-trigger
backdoors. In this paper, we present a novel method to eliminate backdoor
behaviors from LLMs through the construction of information conflicts using
both internal and external mechanisms. Internally, we leverage a lightweight
dataset to train a conflict model, which is then merged with the backdoored
model to neutralize malicious behaviors by embedding contradictory information
within the model's parametric memory. Externally, we incorporate convincing
contradictory evidence into the prompt to challenge the model's internal
backdoor knowledge. Experimental results on classification and conversational
tasks across 4 widely used LLMs demonstrate that our method outperforms 8
state-of-the-art backdoor defense baselines. We can reduce the attack success
rate of advanced backdoor attacks by up to 98% while maintaining over 90% clean
data accuracy. Furthermore, our method has proven to be robust against adaptive
backdoor attacks. The code will be open-sourced upon publication.
