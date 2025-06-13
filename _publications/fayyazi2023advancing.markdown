---
layout: publication
title: 'Advancing TTP Analysis: Harnessing The Power Of Large Language Models With Retrieval Augmented Generation'
authors: Reza Fayyazi, Rozhina Taghdimi, Shanchieh Jay Yang
conference: "Arxiv"
year: 2023
bibkey: fayyazi2023advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00280"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting']
---
Tactics, Techniques, and Procedures (TTPs) outline the methods attackers use
to exploit vulnerabilities. The interpretation of TTPs in the MITRE ATT&CK
framework can be challenging for cybersecurity practitioners due to presumed
expertise and complex dependencies. Meanwhile, advancements with Large Language
Models (LLMs) have led to recent surge in studies exploring its uses in
cybersecurity operations. It is, however, unclear how LLMs can be used in an
efficient and proper way to provide accurate responses for critical domains
such as cybersecurity. This leads us to investigate how to better use two types
of LLMs: small-scale encoder-only (e.g., RoBERTa) and larger decoder-only
(e.g., GPT-3.5) LLMs to comprehend and summarize TTPs with the intended
purposes (i.e., tactics) of a cyberattack procedure. This work studies and
compares the uses of supervised fine-tuning (SFT) of encoder-only LLMs vs.
Retrieval Augmented Generation (RAG) for decoder-only LLMs (without
fine-tuning). Both SFT and RAG techniques presumably enhance the LLMs with
relevant contexts for each cyberattack procedure. Our studies show decoder-only
LLMs with RAG achieves better performance than encoder-only models with SFT,
particularly when directly relevant context is extracted by RAG. The
decoder-only results could suffer low `Precision' while achieving high
`Recall'. Our findings further highlight a counter-intuitive observation that
more generic prompts tend to yield better predictions of cyberattack tactics
than those that are more specifically tailored.
