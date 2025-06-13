---
layout: publication
title: 'Are Large Language Models Good Data Preprocessors?'
authors: Elyas Meguellati, Nardiena Pratama, Shazia Sadiq, Gianluca Demartini
conference: "Arxiv"
year: 2025
bibkey: meguellati2025are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16790"}
tags: ['Multimodal Models', 'Training Techniques', 'GPT', 'Model Architecture']
---
High-quality textual training data is essential for the success of multimodal
data processing tasks, yet outputs from image captioning models like BLIP and
GIT often contain errors and anomalies that are difficult to rectify using
rule-based methods. While recent work addressing this issue has predominantly
focused on using GPT models for data preprocessing on relatively simple public
datasets, there is a need to explore a broader range of Large Language Models
(LLMs) and tackle more challenging and diverse datasets.
  In this study, we investigate the use of multiple LLMs, including LLaMA 3.1
70B, GPT-4 Turbo, and Sonnet 3.5 v2, to refine and clean the textual outputs of
BLIP and GIT. We assess the impact of LLM-assisted data cleaning by comparing
downstream-task (SemEval 2024 Subtask "Multilabel Persuasion Detection in
Memes") models trained on cleaned versus non-cleaned data. While our
experimental results show improvements when using LLM-cleaned captions,
statistical tests reveal that most of these improvements are not significant.
This suggests that while LLMs have the potential to enhance data cleaning and
repairing, their effectiveness may be limited depending on the context they are
applied to, the complexity of the task, and the level of noise in the text.
  Our findings highlight the need for further research into the capabilities
and limitations of LLMs in data preprocessing pipelines, especially when
dealing with challenging datasets, contributing empirical evidence to the
ongoing discussion about integrating LLMs into data preprocessing pipelines.
