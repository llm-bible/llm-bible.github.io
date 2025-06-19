---
layout: publication
title: 'LAVENDER: Unifying Video-language Understanding As Masked Language Modeling'
authors: Linjie Li et al.
conference: Arxiv
year: 2022
citations: 44
bibkey: li2022unifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.07160'}, {name: Code,
    url: 'https://github.com/microsoft/LAVENDER'}]
tags: [Language Modeling, Multimodal Models, Pre-Training, Few-Shot, Masked Language
    Model, BERT]
---
Unified vision-language frameworks have greatly advanced in recent years,
most of which adopt an encoder-decoder architecture to unify image-text tasks
as sequence-to-sequence generation. However, existing video-language (VidL)
models still require task-specific designs in model architecture and training
objectives for each task. In this work, we explore a unified VidL framework
LAVENDER, where Masked Language Modeling (MLM) is used as the common interface
for all pre-training and downstream tasks. Such unification leads to a
simplified model architecture, where only a lightweight MLM head, instead of a
decoder with much more parameters, is needed on top of the multimodal encoder.
Surprisingly, experimental results show that this unified framework achieves
competitive performance on 14 VidL benchmarks, covering video question
answering, text-to-video retrieval and video captioning. Extensive analyses
further demonstrate the advantage of LAVENDER over existing VidL methods in:
(i) supporting all downstream tasks with just a single set of parameter values
when multi-task finetuned; (ii) few-shot generalization on various downstream
tasks; and (iii) enabling zero-shot evaluation on video question answering
tasks. Code is available at https://github.com/microsoft/LAVENDER.