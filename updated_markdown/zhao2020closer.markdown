---
layout: publication
title: 'A Closer Look At Few-shot Crosslingual Transfer: The Choice Of Shots Matters'
authors: Mengjie Zhao et al.
conference: "Arxiv"
year: 2020
citations: 35
bibkey: zhao2020closer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2012.15682'}
tags: ['Attention Mechanism', 'Few-Shot', 'BERT', 'Model Architecture']
---
Few-shot crosslingual transfer has been shown to outperform its zero-shot
counterpart with pretrained encoders like multilingual BERT. Despite its
growing popularity, little to no attention has been paid to standardizing and
analyzing the design of few-shot experiments. In this work, we highlight a
fundamental risk posed by this shortcoming, illustrating that the model
exhibits a high degree of sensitivity to the selection of few shots. We conduct
a large-scale experimental study on 40 sets of sampled few shots for six
diverse NLP tasks across up to 40 languages. We provide an analysis of success
and failure cases of few-shot transfer, which highlights the role of lexical
features. Additionally, we show that a straightforward full model finetuning
approach is quite effective for few-shot transfer, outperforming several
state-of-the-art few-shot approaches. As a step towards standardizing few-shot
crosslingual experimental designs, we make our sampled few shots publicly
available.
