---
layout: publication
title: 'APOLLO: A Simple Approach For Adaptive Pretraining Of Language Models For Logical Reasoning'
authors: Soumya Sanyal, Yichong Xu, Shuohang Wang, Ziyi Yang, Reid Pryzant, Wenhao Yu, Chenguang Zhu, Xiang Ren
conference: "Arxiv"
year: 2022
bibkey: sanyal2022simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09282"}
tags: ['Masked Language Model', 'Training Techniques', 'Language Modeling', 'Pretraining Methods', 'BERT']
---
Logical reasoning of text is an important ability that requires understanding
the information present in the text, their interconnections, and then reasoning
through them to infer new conclusions. Prior works on improving the logical
reasoning ability of language models require complex processing of training
data (e.g., aligning symbolic knowledge to text), yielding task-specific data
augmentation solutions that restrict the learning of general logical reasoning
skills. In this work, we propose APOLLO, an adaptively pretrained language
model that has improved logical reasoning abilities. We select a subset of
Wikipedia, based on a set of logical inference keywords, for continued
pretraining of a language model. We use two self-supervised loss functions: a
modified masked language modeling loss where only specific parts-of-speech
words, that would likely require more reasoning than basic language
understanding, are masked, and a sentence-level classification loss that
teaches the model to distinguish between entailment and contradiction types of
sentences. The proposed training paradigm is both simple and independent of
task formats. We demonstrate the effectiveness of APOLLO by comparing it with
prior baselines on two logical reasoning datasets. APOLLO performs comparably
on ReClor and outperforms baselines on LogiQA. The code base has been made
publicly available.
