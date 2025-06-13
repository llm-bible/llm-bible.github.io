---
layout: publication
title: 'Evaluating Large Language Models As Virtual Annotators For Time-series Physical Sensing Data'
authors: Aritra Hota, Soumyajit Chatterjee, Sandip Chakraborty
conference: "ACM Transactions on Intelligent Systems and Technology 2024"
year: 2024
bibkey: hota2024evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.01133'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Traditional human-in-the-loop-based annotation for time-series data like
inertial data often requires access to alternate modalities like video or audio
from the environment. These alternate sources provide the necessary information
to the human annotator, as the raw numeric data is often too obfuscated even
for an expert. However, this traditional approach has many concerns surrounding
overall cost, efficiency, storage of additional modalities, time, scalability,
and privacy. Interestingly, recent large language models (LLMs) are also
trained with vast amounts of publicly available alphanumeric data, which allows
them to comprehend and perform well on tasks beyond natural language
processing. Naturally, this opens up a potential avenue to explore LLMs as
virtual annotators where the LLMs will be directly provided the raw sensor data
for annotation instead of relying on any alternate modality. Naturally, this
could mitigate the problems of the traditional human-in-the-loop approach.
Motivated by this observation, we perform a detailed study in this paper to
assess whether the state-of-the-art (SOTA) LLMs can be used as virtual
annotators for labeling time-series physical sensing data. To perform this in a
principled manner, we segregate the study into two major phases. In the first
phase, we investigate the challenges an LLM like GPT-4 faces in comprehending
raw sensor data. Considering the observations from phase 1, in the next phase,
we investigate the possibility of encoding the raw sensor data using SOTA SSL
approaches and utilizing the projected time-series data to get annotations from
the LLM. Detailed evaluation with four benchmark HAR datasets shows that
SSL-based encoding and metric-based guidance allow the LLM to make more
reasonable decisions and provide accurate annotations without requiring
computationally expensive fine-tuning or sophisticated prompt engineering.
