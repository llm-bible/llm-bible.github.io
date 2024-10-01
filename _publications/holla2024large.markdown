---
layout: publication
title: 'Large Language Models Aren''t All That You Need'
authors: Holla Kiran Voderhobli, Kumar Chaithanya, Singh Aryan
conference: "Arxiv"
year: 2024
bibkey: holla2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00698"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture']
---
This paper describes the architecture and systems built towards solving the SemEval 2023 Task 2: MultiCoNER II (Multilingual Complex Named Entity Recognition) [1]. We evaluate two approaches (a) a traditional Conditional Random Fields model and (b) a Large Language Model (LLM) fine-tuned with a customized head and compare the two approaches. The novel ideas explored are: 1) Decaying auxiliary loss (with residual) - where we train the model on an auxiliary task of Coarse-Grained NER and include this task as a part of the loss function 2) Triplet token blending - where we explore ways of blending the embeddings of neighboring tokens in the final NER layer prior to prediction 3) Task-optimal heads - where we explore a variety of custom heads and learning rates for the final layer of the LLM. We also explore multiple LLMs including GPT-3 and experiment with a variety of dropout and other hyperparameter settings before arriving at our final model which achieves micro &amp; macro f1 of 0.85/0.84 (on dev) and 0.67/0.61 on the test data . We show that while pre-trained LLMs, by themselves, bring about a large improvement in scores as compared to traditional models, we also demonstrate that tangible improvements to the Macro-F1 score can be made by augmenting the LLM with additional feature/loss/model engineering techniques described above.
