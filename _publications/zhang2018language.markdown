---
layout: publication
title: 'Language Modeling Teaches You More Syntax Than Translation Does: Lessons Learned
  Through Auxiliary Task Analysis'
authors: Kelly W. Zhang, Samuel R. Bowman
conference: Blackbox NLP Workshop EMNLP 2018
year: 2018
citations: 19
bibkey: zhang2018language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.10040'}]
tags: [Language Modeling, Applications, Pre-Training]
---
Recent work using auxiliary prediction task classifiers to investigate the
properties of LSTM representations has begun to shed light on why pretrained
representations, like ELMo (Peters et al., 2018) and CoVe (McCann et al.,
2017), are so beneficial for neural language understanding models. We still,
though, do not yet have a clear understanding of how the choice of pretraining
objective affects the type of linguistic information that models learn. With
this in mind, we compare four objectives---language modeling, translation,
skip-thought, and autoencoding---on their ability to induce syntactic and
part-of-speech information. We make a fair comparison between the tasks by
holding constant the quantity and genre of the training data, as well as the
LSTM architecture. We find that representations from language models
consistently perform best on our syntactic auxiliary prediction tasks, even
when trained on relatively small amounts of data. These results suggest that
language modeling may be the best data-rich pretraining task for transfer
learning applications requiring syntactic information. We also find that the
representations from randomly-initialized, frozen LSTMs perform strikingly well
on our syntactic auxiliary tasks, but this effect disappears when the amount of
training data for the auxiliary tasks is reduced.