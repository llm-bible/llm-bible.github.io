---
layout: publication
title: 'Diasynth: Synthetic Dialogue Generation Framework For Low Resource Dialogue Applications'
authors: Sathya Krishnan Suresh, Wu Mengjun, Tushar Pranav, Eng Siong Chng
conference: "NAACL 2025"
year: 2024
bibkey: suresh2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19020"}
tags: ['Few-Shot', 'Training Techniques', 'Applications', 'Tools']
---
The scarcity of domain-specific dialogue datasets limits the development of
dialogue systems across applications. Existing research is constrained by
general or niche datasets that lack sufficient scale for training dialogue
systems. To address this gap, we introduce DiaSynth - a synthetic dialogue
generation framework capable of generating high-quality, contextually rich
dialogues across a wide range of domains. Unlike existing frameworks, DiaSynth
uses Large Language Models (LLMs) and Chain of Thought (CoT) reasoning to
generate dynamic, domain-specific dialogues with simulated personas and diverse
conversational features. We perform our experiments by generating synthetic
data using different LLMs and few-shot examples from DialogSum and SAMSum. The
pretrained language models fine-tuned on the synthetic data outperform the base
models by 16.47% on dialogue summarization, while the comparison between models
fine-tuned on in-domain data and synthetic data shows that the synthetic data
is able to capture 90.48% of the performance distribution of the in-domain data
on dialogue summarization. The quality of the data generated also increases as
we increase the size of LLM from 3B to 8B. These results validate DiaSynth's
potential as a robust alternative to traditional data collection methods. We
open source the code and data generated for future research.
