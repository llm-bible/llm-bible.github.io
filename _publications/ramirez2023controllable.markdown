---
layout: publication
title: 'Controllable Generation Of Dialogue Acts For Dialogue Systems Via Few-shot Response Generation And Ranking'
authors: Ramirez Angela, Agarwal Karik, Juraska Juraj, Garg Utkarsh, Walker Marilyn A.
conference: "Arxiv"
year: 2023
bibkey: ramirez2023controllable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.14440"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Dialogue systems need to produce responses that realize multiple types of
dialogue acts (DAs) with high semantic fidelity. In the past, natural language
generators (NLGs) for dialogue were trained on large parallel corpora that map
from a domain-specific DA and its semantic attributes to an output utterance.
Recent work shows that pretrained language models (LLMs) offer new
possibilities for controllable NLG using prompt-based learning. Here we develop
a novel few-shot overgenerate-and-rank approach that achieves the controlled
generation of DAs. We compare eight few-shot prompt styles that include a novel
method of generating from textual pseudo-references using a textual style
transfer approach. We develop six automatic ranking functions that identify
outputs with both the correct DA and high semantic accuracy at generation time.
We test our approach on three domains and four LLMs. To our knowledge, this is
the first work on NLG for dialogue that automatically ranks outputs using both
DA and attribute accuracy. For completeness, we compare our results to
fine-tuned few-shot models trained with 5 to 100 instances per DA. Our results
show that several prompt settings achieve perfect DA accuracy, and near perfect
semantic accuracy (99.81%) and perform better than few-shot fine-tuning.
