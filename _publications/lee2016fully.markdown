---
layout: publication
title: Fully Character45;level Neural Machine Translation Without Explicit Segmentation
authors: Lee Jason, Cho Kyunghyun, Hofmann Thomas
conference: "Arxiv"
year: 2016
bibkey: lee2016fully
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1610.03017"}
tags: ['Applications', 'Training Techniques']
---
Most existing machine translation systems operate at the level of words relying on explicit segmentation to extract tokens. We introduce a neural machine translation (NMT) model that maps a source character sequence to a target character sequence without any segmentation. We employ a character45;level convolutional network with max45;pooling at the encoder to reduce the length of source representation allowing the model to be trained at a speed comparable to subword45;level models while capturing local regularities. Our character45;to45;character model outperforms a recently proposed baseline with a subword45;level encoder on WMT15 DE45;EN and CS45;EN and gives comparable performance on FI45;EN and RU45;EN. We then demonstrate that it is possible to share a single character45;level encoder across multiple languages by training a model on a many45;to45;one translation task. In this multilingual setting the character45;level encoder significantly outperforms the subword45;level encoder on all the language pairs. We observe that on CS45;EN FI45;EN and RU45;EN the quality of the multilingual character45;level translation even surpasses the models specifically trained on that language pair alone both in terms of BLEU score and human judgment.
