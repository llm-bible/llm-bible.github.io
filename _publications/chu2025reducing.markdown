---
layout: publication
title: 'Reducing Hallucinations Of Medical Multimodal Large Language Models With Visual Retrieval-augmented Generation'
authors: Yun-wei Chu, Kai Zhang, Christopher Malon, Martin Renqiang Min
conference: "Arxiv"
year: 2025
bibkey: chu2025reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15040'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal Large Language Models (MLLMs) have shown impressive performance in
vision and text tasks. However, hallucination remains a major challenge,
especially in fields like healthcare where details are critical. In this work,
we show how MLLMs may be enhanced to support Visual RAG (V-RAG), a
retrieval-augmented generation framework that incorporates both text and visual
data from retrieved images. On the MIMIC-CXR chest X-ray report generation and
Multicare medical image caption generation datasets, we show that Visual RAG
improves the accuracy of entity probing, which asks whether a medical entities
is grounded by an image. We show that the improvements extend both to frequent
and rare entities, the latter of which may have less positive training data.
Downstream, we apply V-RAG with entity probing to correct hallucinations and
generate more clinically accurate X-ray reports, obtaining a higher RadGraph-F1
score.
