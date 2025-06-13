---
layout: publication
title: 'Exploring Language Model Generalization In Low-resource Extractive QA'
authors: Saptarshi Sengupta, Wenpeng Yin, Preslav Nakov, Shreya Ghosh, Suhang Wang
conference: "Arxiv"
year: 2024
bibkey: sengupta2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18446"}
tags: ['Training Techniques', 'Applications']
---
In this paper, we investigate Extractive Question Answering (EQA) with Large
Language Models (LLMs) under domain drift, i.e., can LLMs generalize to domains
that require specific knowledge such as medicine and law in a zero-shot fashion
without additional in-domain training? To this end, we devise a series of
experiments to explain the performance gap empirically. Our findings suggest
that: (a) LLMs struggle with dataset demands of closed domains such as
retrieving long answer spans; (b) Certain LLMs, despite showing strong overall
performance, display weaknesses in meeting basic requirements as discriminating
between domain-specific senses of words which we link to pre-processing
decisions; (c) Scaling model parameters is not always effective for cross
domain generalization; and (d) Closed-domain datasets are quantitatively much
different than open-domain EQA datasets and current LLMs struggle to deal with
them. Our findings point out important directions for improving existing LLMs.
