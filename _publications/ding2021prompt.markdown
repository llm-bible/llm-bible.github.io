---
layout: publication
title: Prompt-learning For Fine-grained Entity Typing
authors: Ning Ding et al.
conference: Arxiv
year: 2021
citations: 52
bibkey: ding2021prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.10604'}]
tags: [Prompting, Fine-Tuning, Few-Shot, Language Modeling, Masked Language Model,
  BERT]
---
As an effective approach to tune pre-trained language models (PLMs) for
specific tasks, prompt-learning has recently attracted much attention from
researchers. By using \textit\{cloze\}-style language prompts to stimulate the
versatile knowledge of PLMs, prompt-learning can achieve promising results on a
series of NLP tasks, such as natural language inference, sentiment
classification, and knowledge probing. In this work, we investigate the
application of prompt-learning on fine-grained entity typing in fully
supervised, few-shot and zero-shot scenarios. We first develop a simple and
effective prompt-learning pipeline by constructing entity-oriented verbalizers
and templates and conducting masked language modeling. Further, to tackle the
zero-shot regime, we propose a self-supervised strategy that carries out
distribution-level optimization in prompt-learning to automatically summarize
the information of entity types. Extensive experiments on three fine-grained
entity typing benchmarks (with up to 86 classes) under fully supervised,
few-shot and zero-shot settings show that prompt-learning methods significantly
outperform fine-tuning baselines, especially when the training data is
insufficient.