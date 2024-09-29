---
layout: publication
title: Improving Black45;box Robustness With In45;context Rewriting
authors: O'brien Kyle, Ng Nathan, Puri Isha, Mendez Jorge, Palangi Hamid, Kim Yoon, Ghassemi Marzyeh, Hartvigsen Thomas
conference: "Arxiv"
year: 2024
bibkey: obrien2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08225"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Tools', 'Training Techniques']
---
Machine learning models for text classification often excel on in45;distribution (ID) data but struggle with unseen out45;of45;distribution (OOD) inputs. Most techniques for improving OOD robustness are not applicable to settings where the model is effectively a black box such as when the weights are frozen retraining is costly or the model is leveraged via an API. Test45;time augmentation (TTA) is a simple post45;hoc technique for improving robustness that sidesteps black45;box constraints by aggregating predictions across multiple augmentations of the test input. TTA has seen limited use in NLP due to the challenge of generating effective natural language augmentations. In this work we propose LLM45;TTA which uses LLM45;generated augmentations as TTAs augmentation function. LLM45;TTA outperforms conventional augmentation functions across sentiment toxicity and news classification tasks for BERT and T5 models with BERTs OOD robustness improving by an average of 4.48 percentage points without regressing average ID performance. We explore selectively augmenting inputs based on prediction entropy to reduce the rate of expensive LLM augmentations allowing us to maintain performance gains while reducing the average number of generated augmentations by 57.7437;. LLM45;TTA is agnostic to the task model architecture does not require OOD labels and is effective across low and high45;resource settings. We share our data models and code for reproducibility.
