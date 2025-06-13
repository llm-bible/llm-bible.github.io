---
layout: publication
title: 'In-context Learning In Presence Of Spurious Correlations'
authors: Hrayr Harutyunyan, Rafayel Darbinyan, Samvel Karapetyan, Hrant Khachatrian
conference: "Arxiv"
year: 2024
bibkey: harutyunyan2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03140"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
Large language models exhibit a remarkable capacity for in-context learning,
where they learn to solve tasks given a few examples. Recent work has shown
that transformers can be trained to perform simple regression tasks in-context.
This work explores the possibility of training an in-context learner for
classification tasks involving spurious features. We find that the conventional
approach of training in-context learners is susceptible to spurious features.
Moreover, when the meta-training dataset includes instances of only one task,
the conventional approach leads to task memorization and fails to produce a
model that leverages context for predictions. Based on these observations, we
propose a novel technique to train such a learner for a given classification
task. Remarkably, this in-context learner matches and sometimes outperforms
strong methods like ERM and GroupDRO. However, unlike these algorithms, it does
not generalize well to other tasks. We show that it is possible to obtain an
in-context learner that generalizes to unseen tasks by training on a diverse
dataset of synthetic in-context learning instances.
