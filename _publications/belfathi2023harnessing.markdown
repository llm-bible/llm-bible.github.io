---
layout: publication
title: 'Harnessing Gpt-3.5-turbo For Rhetorical Role Prediction In Legal Cases'
authors: Belfathi Anas, Hernandez Nicolas, Monceaux Laura
conference: "JURIX"
year: 2023
bibkey: belfathi2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17413"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Survey Paper', 'Training Techniques', 'Transformer']
---
We propose a comprehensive study of one-stage elicitation techniques for querying a large pre-trained generative transformer (GPT-3.5-turbo) in the rhetorical role prediction task of legal cases. This task is known as requiring textual context to be addressed. Our study explores strategies such as zero-few shots, task specification with definitions and clarification of annotation ambiguities, textual context and reasoning with general prompts and specific questions. We show that the number of examples, the definition of labels, the presentation of the (labelled) textual context and specific questions about this context have a positive influence on the performance of the model. Given non-equivalent test set configurations, we observed that prompting with a few labelled examples from direct context can lead the model to a better performance than a supervised fined-tuned multi-class classifier based on the BERT encoder (weighted F1 score of = 72&#37;). But there is still a gap to reach the performance of the best systems = 86&#37;) in the LegalEval 2023 task which, on the other hand, require dedicated resources, architectures and training.
