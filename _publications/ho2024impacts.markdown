---
layout: publication
title: 'Impacts Of Continued Legal Pre-training And IFT On Llms'' Latent Representations Of Human-defined Legal Concepts'
authors: Shaun Ho
conference: "Arxiv"
year: 2024
bibkey: ho2024impacts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12001"}
tags: ['Fine-Tuning', 'Pre-Training', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
This paper aims to offer AI & Law researchers and practitioners a more
detailed understanding of whether and how continued pre-training and
instruction fine-tuning (IFT) of large language models (LLMs) on legal corpora
increases their utilization of human-defined legal concepts when developing
global contextual representations of input sequences. We compared three models:
Mistral 7B, SaulLM-7B-Base (Mistral 7B with continued pre-training on legal
corpora), and SaulLM-7B-Instruct (with further IFT). This preliminary
assessment examined 7 distinct text sequences from recent AI & Law literature,
each containing a human-defined legal concept. We first compared the
proportions of total attention the models allocated to subsets of tokens
representing the legal concepts. We then visualized patterns of raw attention
score alterations, evaluating whether legal training introduced novel attention
patterns corresponding to structures of human legal knowledge. This inquiry
revealed that (1) the impact of legal training was unevenly distributed across
the various human-defined legal concepts, and (2) the contextual
representations of legal knowledge learned during legal training did not
coincide with structures of human-defined legal concepts. We conclude with
suggestions for further investigation into the dynamics of legal LLM training.
