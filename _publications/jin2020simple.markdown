---
layout: publication
title: A Simple Baseline To Semi-supervised Domain Adaptation For Machine Translation
authors: Di Jin, Zhijing Jin, Joey Tianyi Zhou, Peter Szolovits
conference: Arxiv
year: 2020
citations: 15
bibkey: jin2020simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.08140'}]
tags: [Transformer, Fine-Tuning]
---
State-of-the-art neural machine translation (NMT) systems are data-hungry and
perform poorly on new domains with no supervised data. As data collection is
expensive and infeasible in many cases, domain adaptation methods are needed.
In this work, we propose a simple but effect approach to the semi-supervised
domain adaptation scenario of NMT, where the aim is to improve the performance
of a translation model on the target domain consisting of only non-parallel
data with the help of supervised source domain data. This approach iteratively
trains a Transformer-based NMT model via three training objectives: language
modeling, back-translation, and supervised translation. We evaluate this method
on two adaptation settings: adaptation between specific domains and adaptation
from a general domain to specific domains, and on two language pairs: German to
English and Romanian to English. With substantial performance improvement
achieved---up to +19.31 BLEU over the strongest baseline, and +47.69 BLEU
improvement over the unadapted model---we present this method as a simple but
tough-to-beat baseline in the field of semi-supervised domain adaptation for
NMT.