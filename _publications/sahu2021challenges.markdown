---
layout: publication
title: Challenges In Procedural Multimodal Machine Comprehensiona Novel Way To Benchmark
authors: Sahu Pritish, Sikka Karan, Divakaran Ajay
conference: "Arxiv"
year: 2021
bibkey: sahu2021challenges
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.11899"}
tags: ['Ethics And Bias', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
We focus on Multimodal Machine Reading Comprehension (M3C) where a model is expected to answer questions based on given passage (or context) and the context and the questions can be in different modalities. Previous works such as RecipeQA have proposed datasets and cloze45;style tasks for evaluation. However we identify three critical biases stemming from the question45;answer generation process and memorization capabilities of large deep models. These biases makes it easier for a model to overfit by relying on spurious correlations or naive data patterns. We propose a systematic framework to address these biases through three Control45;Knobs that enable us to generate a test bed of datasets of progressive difficulty levels. We believe that our benchmark (referred to as Meta45;RecipeQA) will provide for the first time a fine grained estimate of a models generalization capabilities. We also propose a general M3C model that is used to realize several prior SOTA models and motivate a novel hierarchical transformer based reasoning network (HTRN). We perform a detailed evaluation of these models with different language and visual features on our benchmark. We observe a consistent improvement with HTRN over SOTA (~1837; in Visual Cloze task and ~1337; in average over all the tasks). We also observe a drop in performance across all the models when testing on RecipeQA and proposed Meta45;RecipeQA (e.g. 83.637; versus 67.137; for HTRN) which shows that the proposed dataset is relatively less biased. We conclude by highlighting the impact of the control knobs with some quantitative results.
