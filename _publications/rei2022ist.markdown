---
layout: publication
title: 'Cometkiwi: Ist-unbabel 2022 Submission For The Quality Estimation Shared Task'
authors: Ricardo Rei et al.
conference: "Arxiv"
year: 2022
citations: 30
bibkey: rei2022ist
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2209.06243'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'WMT', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods']
---
We present the joint contribution of IST and Unbabel to the WMT 2022 Shared
Task on Quality Estimation (QE). Our team participated on all three subtasks:
(i) Sentence and Word-level Quality Prediction; (ii) Explainable QE; and (iii)
Critical Error Detection. For all tasks we build on top of the COMET framework,
connecting it with the predictor-estimator architecture of OpenKiwi, and
equipping it with a word-level sequence tagger and an explanation extractor.
Our results suggest that incorporating references during pretraining improves
performance across several language pairs on downstream tasks, and that jointly
training with sentence and word-level objectives yields a further boost.
Furthermore, combining attention and gradient information proved to be the top
strategy for extracting good explanations of sentence-level QE models. Overall,
our submissions achieved the best results for all three tasks for almost all
language pairs by a considerable margin.
