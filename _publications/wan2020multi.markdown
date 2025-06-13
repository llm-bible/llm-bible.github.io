---
layout: publication
title: 'Multi-task Learning With Multi-head Attention For Multi-choice Reading Comprehension'
authors: Hui Wan
conference: "Arxiv"
year: 2020
bibkey: wan2020multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2003.04992'}
tags: ['Attention Mechanism', 'Transformer', 'BERT', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Multiple-choice Machine Reading Comprehension (MRC) is an important and
challenging Natural Language Understanding (NLU) task, in which a machine must
choose the answer to a question from a set of choices, with the question placed
in context of text passages or dialog. In the last a couple of years the NLU
field has been revolutionized with the advent of models based on the
Transformer architecture, which are pretrained on massive amounts of
unsupervised data and then fine-tuned for various supervised learning NLU
tasks. Transformer models have come to dominate a wide variety of leader-boards
in the NLU field; in the area of MRC, the current state-of-the-art model on the
DREAM dataset (see[Sunet al., 2019]) fine tunes Albert, a large pretrained
Transformer-based model, and addition-ally combines it with an extra layer of
multi-head attention between context and question-answer[Zhuet al., 2020].The
purpose of this note is to document a new state-of-the-art result in the DREAM
task, which is accomplished by, additionally, performing multi-task learning on
two MRC multi-choice reading comprehension tasks (RACE and DREAM).
