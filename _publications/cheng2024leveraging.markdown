---
layout: publication
title: 'Leveraging The Context Through Multi-round Interactions For Jailbreaking Attacks'
authors: Yixin Cheng, Markos Georgopoulos, Volkan Cevher, Grigorios G. Chrysos
conference: "Arxiv"
year: 2024
bibkey: cheng2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09177"}
tags: ['Security', 'RAG', 'GPT', 'Pretraining Methods']
---
Large Language Models (LLMs) are susceptible to Jailbreaking attacks, which
aim to extract harmful information by subtly modifying the attack query. As
defense mechanisms evolve, directly obtaining harmful information becomes
increasingly challenging for Jailbreaking attacks. In this work, inspired from
Chomsky's transformational-generative grammar theory and human practices of
indirect context to elicit harmful information, we focus on a new attack form,
called Contextual Interaction Attack. We contend that the prior
context\u2014the information preceding the attack query\u2014plays a pivotal
role in enabling strong Jailbreaking attacks. Specifically, we propose a first
multi-turn approach that leverages benign preliminary questions to interact
with the LLM. Due to the autoregressive nature of LLMs, which use previous
conversation rounds as context during generation, we guide the model's
question-response pair to construct a context that is semantically aligned with
the attack query to execute the attack. We conduct experiments on seven
different LLMs and demonstrate the efficacy of this attack, which is black-box
and can also transfer across LLMs. We believe this can lead to further
developments and understanding of security in LLMs.
