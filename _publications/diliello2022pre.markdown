---
layout: publication
title: 'Pre-training Transformer Models With Sentence-level Objectives For Answer Sentence Selection'
authors: Luca Di Liello, Siddhant Garg, Luca Soldaini, Alessandro Moschitti
conference: "Arxiv"
year: 2022
bibkey: diliello2022pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.10455"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'BERT', 'Transformer', 'Pre-Training']
---
An important task for designing QA systems is answer sentence selection
(AS2): selecting the sentence containing (or constituting) the answer to a
question from a set of retrieved relevant documents. In this paper, we propose
three novel sentence-level transformer pre-training objectives that incorporate
paragraph-level semantics within and across documents, to improve the
performance of transformers for AS2, and mitigate the requirement of large
labeled datasets. Specifically, the model is tasked to predict whether: (i) two
sentences are extracted from the same paragraph, (ii) a given sentence is
extracted from a given paragraph, and (iii) two paragraphs are extracted from
the same document. Our experiments on three public and one industrial AS2
datasets demonstrate the empirical superiority of our pre-trained transformers
over baseline models such as RoBERTa and ELECTRA for AS2.
