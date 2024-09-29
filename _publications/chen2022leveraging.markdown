---
layout: publication
title: Leveraging Natural Supervision For Language Representation Learning And Generation
authors: Chen Mingda
conference: "Arxiv"
year: 2022
bibkey: chen2022leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.10617"}
tags: ['Applications', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent breakthroughs in Natural Language Processing (NLP) have been driven by language models trained on a massive amount of plain text. While powerful deriving supervision from textual resources is still an open question. For example language model pretraining often neglects the rich freely45;available structures in textual data. In this thesis we describe three lines of work that seek to improve the training and evaluation of neural models using naturally45;occurring supervision. We first investigate self45;supervised training losses to help enhance the performance of pretrained language models for various NLP tasks. Specifically we alter the sentence prediction loss to make it better suited to other pretraining losses and more challenging to solve. We design an intermediate finetuning step that uses self45;supervised training to promote models ability in cross45;task generalization. Then we describe methods to leverage the structures in Wikipedia and paraphrases. In particular we propose training losses to exploit hyperlinks article structures and article category graphs for entity45; discourse45; entailment45;related knowledge. We propose a framework that uses paraphrase pairs to disentangle semantics and syntax in sentence representations. We extend the framework for a novel generation task that controls the syntax of output text with a sentential exemplar. Lastly we discuss our work on tailoring textual resources for establishing challenging evaluation tasks. We introduce three datasets by defining novel tasks using various fan45;contributed websites including a long45;form data45;to45;text generation dataset a screenplay summarization dataset and a long45;form story generation dataset. These datasets have unique characteristics offering challenges to future work in their respective task settings.
