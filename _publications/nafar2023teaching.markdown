---
layout: publication
title: 'Teaching Probabilistic Logical Reasoning To Transformers'
authors: Nafar Aliakbar, Venable Kristen Brent, Kordjamshidi Parisa
conference: "Arxiv"
year: 2023
bibkey: nafar2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13179"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
In this paper we evaluate the capability of transformer-based language models in making inferences over uncertain text that includes uncertain rules of reasoning. We cover both Pre-trained Language Models (PLMs) and generative Large Language Models (LLMs). Our evaluation results show that both generations of language models struggle with reasoning over uncertain text. We propose a novel end-to-end fine-tuning approach Probabilistic Constraint Training (PCT) that utilizes probabilistic logical rules as constraints in the fine-tuning phase without relying on these rules in the inference stage. To assess the effectiveness of PCT we utilize the related corpora and additionally create a new and more challenging benchmark that unlike the previous ones uses instance-specific rules. Our study demonstrates that PCT improves the transformer-based language models intrinsic reasoning and makes their probabilistic logical reasoning process more explicit and explainable. Furthermore PCT equips these models to effectively handle novel situations including higher reasoning depth new domains and complex probabilistic structures.
