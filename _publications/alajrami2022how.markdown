---
layout: publication
title: 'How Does The Pre-training Objective Affect What Large Language Models Learn About Linguistic Properties?'
authors: Ahmed Alajrami, Nikolaos Aletras
conference: "Arxiv"
year: 2022
bibkey: alajrami2022how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.10415"}
tags: ['Masked Language Model', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'BERT', 'Pre-Training']
---
Several pre-training objectives, such as masked language modeling (MLM), have
been proposed to pre-train language models (e.g. BERT) with the aim of learning
better language representations. However, to the best of our knowledge, no
previous work so far has investigated how different pre-training objectives
affect what BERT learns about linguistics properties. We hypothesize that
linguistically motivated objectives such as MLM should help BERT to acquire
better linguistic knowledge compared to other non-linguistically motivated
objectives that are not intuitive or hard for humans to guess the association
between the input and the label to be predicted. To this end, we pre-train BERT
with two linguistically motivated objectives and three non-linguistically
motivated ones. We then probe for linguistic characteristics encoded in the
representation of the resulting models. We find strong evidence that there are
only small differences in probing performance between the representations
learned by the two different types of objectives. These surprising results
question the dominant narrative of linguistically informed pre-training.
