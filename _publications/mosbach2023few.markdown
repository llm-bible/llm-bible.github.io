---
layout: publication
title: 'Few-shot Fine-tuning Vs. In-context Learning: A Fair Comparison And Evaluation'
authors: Marius Mosbach, Tiago Pimentel, Shauli Ravfogel, Dietrich Klakow, Yanai Elazar
conference: Arxiv
year: 2023
citations: 29
bibkey: mosbach2023few
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.16938'}]
tags: [Fine-Tuning, Few-Shot, In-Context Learning]
---
Few-shot fine-tuning and in-context learning are two alternative strategies
for task adaptation of pre-trained language models. Recently, in-context
learning has gained popularity over fine-tuning due to its simplicity and
improved out-of-domain generalization, and because extensive evidence shows
that fine-tuned models pick up on spurious correlations. Unfortunately,
previous comparisons of the two approaches were done using models of different
sizes. This raises the question of whether the observed weaker out-of-domain
generalization of fine-tuned models is an inherent property of fine-tuning or a
limitation of the experimental setup. In this paper, we compare the
generalization of few-shot fine-tuning and in-context learning to challenge
datasets, while controlling for the models used, the number of examples, and
the number of parameters, ranging from 125M to 30B. Our results show that
fine-tuned language models can in fact generalize well out-of-domain. We find
that both approaches generalize similarly; they exhibit large variation and
depend on properties such as model size and the number of examples,
highlighting that robust task adaptation remains a challenge.