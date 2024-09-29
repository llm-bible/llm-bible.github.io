---
layout: publication
title: SLM Learning A Discourse Language Representation With Sentence Unshuffling
authors: Lee Haejun, Hudson Drew A., Lee Kangwook, Manning Christopher D.
conference: "Arxiv"
year: 2020
bibkey: lee2020learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.16249"}
tags: ['BERT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We introduce Sentence45;level Language Modeling a new pre45;training objective for learning a discourse language representation in a fully self45;supervised manner. Recent pre45;training methods in NLP focus on learning either bottom or top45;level language representations contextualized word representations derived from language model objectives at one extreme and a whole sequence representation learned by order classification of two given textual segments at the other. However these models are not directly encouraged to capture representations of intermediate45;size structures that exist in natural languages such as sentences and the relationships among them. To that end we propose a new approach to encourage learning of a contextualized sentence45;level representation by shuffling the sequence of input sentences and training a hierarchical transformer model to reconstruct the original ordering. Through experiments on downstream tasks such as GLUE SQuAD and DiscoEval we show that this feature of our model improves the performance of the original BERT by large margins.
