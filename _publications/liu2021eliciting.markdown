---
layout: publication
title: 'Mirrorwic: On Eliciting Word-in-context Representations From Pretrained Language Models'
authors: Qianchu Liu, Fangyu Liu, Nigel Collier, Anna Korhonen, Ivan Vulić
conference: "Arxiv"
year: 2021
bibkey: liu2021eliciting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.09237"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'BERT', 'Fine-Tuning']
---
Recent work indicated that pretrained language models (PLMs) such as BERT and
RoBERTa can be transformed into effective sentence and word encoders even via
simple self-supervised techniques. Inspired by this line of work, in this paper
we propose a fully unsupervised approach to improving word-in-context (WiC)
representations in PLMs, achieved via a simple and efficient WiC-targeted
fine-tuning procedure: MirrorWiC. The proposed method leverages only raw texts
sampled from Wikipedia, assuming no sense-annotated data, and learns
context-aware word representations within a standard contrastive learning
setup. We experiment with a series of standard and comprehensive WiC benchmarks
across multiple languages. Our proposed fully unsupervised MirrorWiC models
obtain substantial gains over off-the-shelf PLMs across all monolingual,
multilingual and cross-lingual setups. Moreover, on some standard WiC
benchmarks, MirrorWiC is even on-par with supervised models fine-tuned with
in-task data and sense labels.
