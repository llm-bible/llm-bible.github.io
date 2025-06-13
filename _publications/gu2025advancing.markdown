---
layout: publication
title: 'Radalign: Advancing Radiology Report Generation With Vision-language Concept Alignment'
authors: Difei Gu, Yunhe Gao, Yang Zhou, Mu Zhou, Dimitris Metaxas
conference: "Arxiv"
year: 2025
bibkey: gu2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07525"}
  - {name: "Code", url: "https://github.com/difeigu/RadAlign"}
tags: ['Multimodal Models', 'Tools', 'RAG', 'Has Code', 'Interpretability and Explainability', 'Prompting']
---
Automated chest radiographs interpretation requires both accurate disease
classification and detailed radiology report generation, presenting a
significant challenge in the clinical workflow. Current approaches either focus
on classification accuracy at the expense of interpretability or generate
detailed but potentially unreliable reports through image captioning
techniques. In this study, we present RadAlign, a novel framework that combines
the predictive accuracy of vision-language models (VLMs) with the reasoning
capabilities of large language models (LLMs). Inspired by the radiologist's
workflow, RadAlign first employs a specialized VLM to align visual features
with key medical concepts, achieving superior disease classification with an
average AUC of 0.885 across multiple diseases. These recognized medical
conditions, represented as text-based concepts in the aligned visual-language
space, are then used to prompt LLM-based report generation. Enhanced by a
retrieval-augmented generation mechanism that grounds outputs in similar
historical cases, RadAlign delivers superior report quality with a GREEN score
of 0.678, outperforming state-of-the-art methods' 0.634. Our framework
maintains strong clinical interpretability while reducing hallucinations,
advancing automated medical imaging and report analysis through integrated
predictive and generative AI. Code is available at
https://github.com/difeigu/RadAlign.
