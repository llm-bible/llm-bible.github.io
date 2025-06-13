---
layout: publication
title: 'Spurious Correlations And Beyond: Understanding And Mitigating Shortcut Learning In SDOH Extraction With Large Language Models'
authors: Fardin Ahsan Sakib, Ziwei Zhu, Karen Trister Grace, Meliha Yetisgen, Ozlem Uzuner
conference: "Arxiv"
year: 2025
bibkey: sakib2025spurious
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00134'}
tags: ['Prompting']
---
Social determinants of health (SDOH) extraction from clinical text is critical for downstream healthcare analytics. Although large language models (LLMs) have shown promise, they may rely on superficial cues leading to spurious predictions. Using the MIMIC portion of the SHAC (Social History Annotation Corpus) dataset and focusing on drug status extraction as a case study, we demonstrate that mentions of alcohol or smoking can falsely induce models to predict current/past drug use where none is present, while also uncovering concerning gender disparities in model performance. We further evaluate mitigation strategies - such as prompt engineering and chain-of-thought reasoning - to reduce these false positives, providing insights into enhancing LLM reliability in health domains.
