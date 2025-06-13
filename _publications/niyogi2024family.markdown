---
layout: publication
title: 'Paramanu: A Family Of Novel Efficient Generative Foundation Language Models For Indian Languages'
authors: Mitodru Niyogi, Arnab Bhattacharya
conference: "Arxiv"
year: 2024
bibkey: niyogi2024family
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.18034"}
tags: ['Fine-Tuning', 'Applications', 'Tokenization', 'Language Modeling']
---
We present "Paramanu", a family of novel language models (LM) for Indian
languages, consisting of auto-regressive monolingual, bilingual, and
multilingual models pretrained from scratch. Currently, it covers 10 languages
(Assamese, Bangla, Hindi, Konkani, Maithili, Marathi, Odia, Sanskrit, Tamil,
Telugu) across 5 scripts (Bangla, Devanagari, Odia, Tamil, Telugu). The models
are pretrained on a single GPU with context size of 1024 and vary in size from
13.29 million (M) to 367.5 M parameters. We proposed a RoPE embedding scaling
method that enables us to pretrain language models from scratch at larger
sequence length context size than typical GPU memory permits. We also
introduced a novel efficient Indic tokenizer, "mBharat", using a combination of
BPE and Unigram, achieving the least fertility score and the ability to
tokenize unseen languages in both the same script & Roman script. We also
proposed and performed language-specific tokenization for multilingual models &
domain-specific tokenization for monolingual models. To address the "curse of
multilinguality" in our mParamanu model, we pretrained on comparable corpora
based on typological grouping within the same script. Our findings show a
language transfer phenomenon from low-resource to high-resource languages
within languages of the same script & typology. Human evaluations for
open-ended text generation demonstrated that Paramanu models outperformed
several LLMs, despite being 20 to 64 times smaller. We created
instruction-tuning datasets & instruction-tuned our models on 23,000
instructions in respective languages. Comparisons with multilingual LLMs across
various benchmarks for natural language (NL) understanding, NL inference, &
reading comprehension highlight the advantages of our models; leads to the
conclusion that high quality generative LM are possible without high amount of
compute power & enormous number of parameters.
