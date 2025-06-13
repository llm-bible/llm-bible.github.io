---
layout: publication
title: 'The Truth Is In There: Improving Reasoning In Language Models With Layer-selective Rank Reduction'
authors: Pratyusha Sharma, Jordan T. Ash, Dipendra Misra
conference: "Arxiv"
year: 2023
bibkey: sharma2023truth
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.13558'}
tags: ['Training Techniques', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Transformer-based Large Language Models (LLMs) have become a fixture in
modern machine learning. Correspondingly, significant resources are allocated
towards research that aims to further advance this technology, typically
resulting in models of increasing size that are trained on increasing amounts
of data. This work, however, demonstrates the surprising result that it is
often possible to significantly improve the performance of LLMs by selectively
removing higher-order components of their weight matrices. This simple
intervention, which we call LAyer-SElective Rank reduction (LASER), can be done
on a model after training has completed, and requires no additional parameters
or data. We show extensive experiments demonstrating the generality of this
finding across language models and datasets, and provide in-depth analyses
offering insights into both when LASER is effective and the mechanism by which
it operates.
