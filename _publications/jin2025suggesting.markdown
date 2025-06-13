---
layout: publication
title: 'Suggesting Code Edits In Interactive Machine Learning Notebooks Using Large Language Models'
authors: Bihui Jin, Jiayue Wang, Pengyu Nie
conference: "Arxiv"
year: 2025
bibkey: jin2025suggesting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09745"}
tags: ['RAG', 'Training Techniques', 'Reinforcement Learning']
---
Machine learning developers frequently use interactive computational
notebooks, such as Jupyter notebooks, to host code for data processing and
model training. Jupyter notebooks provide a convenient tool for writing machine
learning pipelines and interactively observing outputs, however, maintaining
Jupyter notebooks, e.g., to add new features or fix bugs, can be challenging
due to the length and complexity of the notebooks. Moreover, there is no
existing benchmark related to developer edits on Jupyter notebooks. To address
this, we present the first dataset of 48,398 Jupyter notebook edits derived
from 20,095 revisions of 792 machine learning repositories on GitHub, and
perform the first study of the using LLMs to predict code edits in Jupyter
notebooks. Our dataset captures granular details of cell-level and line-level
modifications, offering a foundation for understanding real-world maintenance
patterns in machine learning workflows. We observed that the edits on Jupyter
notebooks are highly localized, with changes averaging only 166 lines of code
in repositories. While larger models outperform smaller counterparts in code
editing, all models have low accuracy on our dataset even after finetuning,
demonstrating the complexity of real-world machine learning maintenance tasks.
Our findings emphasize the critical role of contextual information in improving
model performance and point toward promising avenues for advancing large
language models' capabilities in engineering machine learning code.
