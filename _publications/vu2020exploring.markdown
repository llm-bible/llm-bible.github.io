---
layout: publication
title: Exploring And Predicting Transferability Across NLP Tasks
authors: Tu Vu et al.
conference: Arxiv
year: 2020
citations: 26
bibkey: vu2020exploring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00770'}]
tags: [Fine-Tuning, Language Modeling]
---
Recent advances in NLP demonstrate the effectiveness of training large-scale
language models and transferring them to downstream tasks. Can fine-tuning
these models on tasks other than language modeling further improve performance?
In this paper, we conduct an extensive study of the transferability between 33
NLP tasks across three broad classes of problems (text classification, question
answering, and sequence labeling). Our results show that transfer learning is
more beneficial than previously thought, especially when target task data is
scarce, and can improve performance even when the source task is small or
differs substantially from the target task (e.g., part-of-speech tagging
transfers well to the DROP QA dataset). We also develop task embeddings that
can be used to predict the most transferable source tasks for a given target
task, and we validate their effectiveness in experiments controlled for source
and target data size. Overall, our experiments reveal that factors such as
source data size, task and domain similarity, and task complexity all play a
role in determining transferability.