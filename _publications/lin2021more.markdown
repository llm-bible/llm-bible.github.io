---
layout: publication
title: 'MDQE: A More Accurate Direct Pretraining For Machine Translation Quality Estimation'
authors: Lei Lin
conference: "Arxiv"
year: 2021
bibkey: lin2021more
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2107.14600'}
tags: ['Training Techniques', 'BERT', 'Tools', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
It is expensive to evaluate the results of Machine Translation(MT), which
usually requires manual translation as a reference. Machine Translation Quality
Estimation (QE) is a task of predicting the quality of machine translations
without relying on any reference. Recently, the emergence of
predictor-estimator framework which trains the predictor as a feature extractor
and estimator as a QE predictor, and pre-trained language models(PLM) have
achieved promising QE performance. However, we argue that there are still gaps
between the predictor and the estimator in both data quality and training
objectives, which preclude QE models from benefiting from a large number of
parallel corpora more directly. Based on previous related work that have
alleviated gaps to some extent, we propose a novel framework that provides a
more accurate direct pretraining for QE tasks. In this framework, a generator
is trained to produce pseudo data that is closer to the real QE data, and a
estimator is pretrained on these data with novel objectives that are the same
as the QE task. Experiments on widely used benchmarks show that our proposed
framework outperforms existing methods, without using any pretraining models
such as BERT.
