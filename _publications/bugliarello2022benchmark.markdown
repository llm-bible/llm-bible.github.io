---
layout: publication
title: 'IGLUE: A Benchmark For Transfer Learning Across Modalities, Tasks, And Languages'
authors: Emanuele Bugliarello et al.
conference: Arxiv
year: 2022
citations: 22
bibkey: bugliarello2022benchmark
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.11732'}]
tags: [Multimodal Models, Few-Shot, Fine-Tuning]
---
Reliable evaluation benchmarks designed for replicability and
comprehensiveness have driven progress in machine learning. Due to the lack of
a multilingual benchmark, however, vision-and-language research has mostly
focused on English language tasks. To fill this gap, we introduce the
Image-Grounded Language Understanding Evaluation benchmark. IGLUE brings
together - by both aggregating pre-existing datasets and creating new ones -
visual question answering, cross-modal retrieval, grounded reasoning, and
grounded entailment tasks across 20 diverse languages. Our benchmark enables
the evaluation of multilingual multimodal models for transfer learning, not
only in a zero-shot setting, but also in newly defined few-shot learning
setups. Based on the evaluation of the available state-of-the-art models, we
find that translate-test transfer is superior to zero-shot transfer and that
few-shot learning is hard to harness for many tasks. Moreover, downstream
performance is partially explained by the amount of available unlabelled
textual data for pretraining, and only weakly by the typological distance of
target-source languages. We hope to encourage future research efforts in this
area by releasing the benchmark to the community.