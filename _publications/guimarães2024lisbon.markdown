---
layout: publication
title: 'Lisbon Computational Linguists At Semeval-2024 Task 2: Using A Mistral 7B Model And Data Augmentation'
authors: Artur Guimarães, Bruno Martins, João Magalhães
conference: "Proceedings of the 18th International Workshop on Semantic Evaluation (SemEval-2024) (2024) 1280-1287"
year: 2024
bibkey: guimarães2024lisbon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03127"}
tags: ['Training Techniques', 'Prompting']
---
This paper describes our approach to the SemEval-2024 safe biomedical Natural
Language Inference for Clinical Trials (NLI4CT) task, which concerns
classifying statements about Clinical Trial Reports (CTRs). We explored the
capabilities of Mistral-7B, a generalist open-source Large Language Model
(LLM). We developed a prompt for the NLI4CT task, and fine-tuned a quantized
version of the model using an augmented version of the training dataset. The
experimental results show that this approach can produce notable results in
terms of the macro F1-score, while having limitations in terms of faithfulness
and consistency. All the developed code is publicly available on a GitHub
repository
