---
layout: publication
title: Deriving Machine Attention From Human Rationales
authors: Yujia Bao, Shiyu Chang, Mo Yu, Regina Barzilay
conference: Arxiv
year: 2018
citations: 20
bibkey: bao2018deriving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.09367'}]
tags: [Attention Mechanism, Model Architecture]
---
Attention-based models are successful when trained on large amounts of data.
In this paper, we demonstrate that even in the low-resource scenario, attention
can be learned effectively. To this end, we start with discrete human-annotated
rationales and map them into continuous attention. Our central hypothesis is
that this mapping is general across domains, and thus can be transferred from
resource-rich domains to low-resource ones. Our model jointly learns a
domain-invariant representation and induces the desired mapping between
rationales and attention. Our empirical results validate this hypothesis and
show that our approach delivers significant gains over state-of-the-art
baselines, yielding over 15% average error reduction on benchmark datasets.