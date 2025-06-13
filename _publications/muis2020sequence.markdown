---
layout: publication
title: 'Sequence-to-sequence Learning For Indonesian Automatic Question Generator'
authors: Ferdiant Joshua 1 And 2 Muis, Ayu 1 And 2 Purwarianti
conference: "2020 International Conference on Advanced Informatics Concept Theory and Application (ICAICTA)"
year: 2020
bibkey: muis2020sequence
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2009.13889'}
tags: ['RAG', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Automatic question generation is defined as the task of automating the
creation of question given a various of textual data. Research in automatic
question generator (AQG) has been conducted for more than 10 years, mainly
focused on factoid question. In all these studies, the state-of-the-art is
attained using sequence-to-sequence approach. However, AQG system for
Indonesian has not ever been researched intensely. In this work we construct an
Indonesian automatic question generator, adapting the architecture from some
previous works. In summary, we used sequence-to-sequence approach using BiGRU,
BiLSTM, and Transformer with additional linguistic features, copy mechanism,
and coverage mechanism. Since there is no public large dan popular Indonesian
dataset for question generation, we translated SQuAD v2.0 factoid question
answering dataset, with additional Indonesian TyDiQA dev set for testing. The
system achieved BLEU1, BLEU2, BLEU3, BLEU4, and ROUGE-L score at 38,35, 20,96,
10,68, 5,78, and 43,4 for SQuAD, and 39.9, 20.78, 10.26, 6.31, 44.13 for
TyDiQA, respectively. The system performed well when the expected answers are
named entities and are syntactically close with the context explaining them.
Additionally, from native Indonesian perspective, the best questions generated
by our best models on their best cases are acceptable and reasonably useful.
