---
layout: publication
title: 'Deceiving Question-answering Models: A Hybrid Word-level Adversarial Approach'
authors: Jiyao Li, Mingze Ni, Yongshun Gong, Wei Liu
conference: "Arxiv"
year: 2024
bibkey: li2024deceiving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08248"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Attention Mechanism']
---
Deep learning underpins most of the currently advanced natural language
processing (NLP) tasks such as textual classification, neural machine
translation (NMT), abstractive summarization and question-answering (QA).
However, the robustness of the models, particularly QA models, against
adversarial attacks is a critical concern that remains insufficiently explored.
This paper introduces QA-Attack (Question Answering Attack), a novel word-level
adversarial strategy that fools QA models. Our attention-based attack exploits
the customized attention mechanism and deletion ranking strategy to identify
and target specific words within contextual passages. It creates deceptive
inputs by carefully choosing and substituting synonyms, preserving grammatical
integrity while misleading the model to produce incorrect responses. Our
approach demonstrates versatility across various question types, particularly
when dealing with extensive long textual inputs. Extensive experiments on
multiple benchmark datasets demonstrate that QA-Attack successfully deceives
baseline QA models and surpasses existing adversarial techniques regarding
success rate, semantics changes, BLEU score, fluency and grammar error rate.
