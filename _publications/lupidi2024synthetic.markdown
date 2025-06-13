---
layout: publication
title: 'Source2synth: Synthetic Data Generation And Curation Grounded In Real Data Sources'
authors: Alisia Lupidi, Carlos Gemmell, Nicola Cancedda, Jane Dwivedi-yu, Jason Weston, Jakob Foerster, Roberta Raileanu, Maria Lomeli
conference: "Arxiv"
year: 2024
bibkey: lupidi2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08239"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Large Language Models still struggle in challenging scenarios that leverage
structured data, complex reasoning, or tool usage. In this paper, we propose
Source2Synth: a new method that can be used for teaching LLMs new skills
without relying on costly human annotations. Source2Synth takes as input a
custom data source and produces synthetic data points with intermediate
reasoning steps grounded in real-world sources. Source2Synth improves the
dataset quality by discarding low-quality generations based on their
answerability. We demonstrate the generality of this approach by applying it to
two challenging domains: we test reasoning abilities in multi-hop question
answering (MHQA), and tool usage in tabular question answering (TQA). Our
method improves performance by 25.51% for TQA on WikiSQL and 22.57% for MHQA on
HotPotQA compared to the fine-tuned baselines.
