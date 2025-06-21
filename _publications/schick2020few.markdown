---
layout: publication
title: Few-shot Text Generation With Pattern-exploiting Training
authors: "Timo Schick, Hinrich Sch\xFCtze"
conference: Arxiv
year: 2020
citations: 77
bibkey: schick2020few
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.11926'}]
tags: [Language Modeling, Few-Shot]
---
Providing pretrained language models with simple task descriptions in natural
language enables them to solve some tasks in a fully unsupervised fashion.
Moreover, when combined with regular learning from examples, this idea yields
impressive few-shot results for a wide range of text classification tasks. It
is also a promising direction to improve data efficiency in generative
settings, but there are several challenges to using a combination of task
descriptions and example-based learning for text generation. In particular, it
is crucial to find task descriptions that are easy to understand for the
pretrained model and to ensure that it actually makes good use of them;
furthermore, effective measures against overfitting have to be implemented. In
this paper, we show how these challenges can be tackled: We introduce GenPET, a
method for text generation that is based on pattern-exploiting training, a
recent approach for combining textual instructions with supervised learning
that only works for classification tasks. On several summarization and headline
generation datasets, GenPET gives consistent improvements over strong baselines
in few-shot settings.