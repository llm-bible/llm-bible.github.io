---
layout: publication
title: Scaling Synthetic Logical Reasoning Datasets With Context45;sensitive Declarative Grammars
authors: Sileo Damien
conference: "Arxiv"
year: 2024
bibkey: sileo2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11035"}
tags: ['BERT', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Tools', 'Training Techniques']
---
Logical reasoning remains a challenge for natural language processing but it can be improved by training language models to mimic theorem provers on procedurally generated problems. Previous work used domain45;specific proof generation algorithms which biases reasoning toward specific proof traces and limits auditability and extensibility. We present a simpler and more general declarative framework with flexible context45;sensitive rules binding multiple languages (specifically simplified English and the TPTP theorem45;proving language). We construct first45;order logic problems by selecting up to 32 premises and one hypothesis. We demonstrate that using semantic constraints during generation and careful English verbalization of predicates enhances logical reasoning without hurting natural English tasks. We use relatively small DeBERTa45;v3 models to achieve state45;of45;the45;art accuracy on the FOLIO human45;authored logic dataset surpassing GPT45;4 in accuracy with or without an external solver by 1237;.
