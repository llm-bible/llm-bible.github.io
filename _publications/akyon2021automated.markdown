---
layout: publication
title: 'Automated Question Generation And Question Answering From Turkish Texts'
authors: Fatih Cagatay Akyon, Devrim Cavusoglu, Cemil Cengiz, Sinan Onur Altinuc, Alptekin Temizel
conference: "Arxiv"
year: 2021
bibkey: akyon2021automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.06476"}
  - {name: "Code", url: "https://github.com/obss/turkish-question-generation"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
While exam-style questions are a fundamental educational tool serving a
variety of purposes, manual construction of questions is a complex process that
requires training, experience and resources. Automatic question generation (QG)
techniques can be utilized to satisfy the need for a continuous supply of new
questions by streamlining their generation. However, compared to automatic
question answering (QA), QG is a more challenging task. In this work, we
fine-tune a multilingual T5 (mT5) transformer in a multi-task setting for QA,
QG and answer extraction tasks using Turkish QA datasets. To the best of our
knowledge, this is the first academic work that performs automated text-to-text
question generation from Turkish texts. Experimental evaluations show that the
proposed multi-task setting achieves state-of-the-art Turkish question
answering and question generation performance on TQuADv1, TQuADv2 datasets and
XQuAD Turkish split. The source code and the pre-trained models are available
at https://github.com/obss/turkish-question-generation.
