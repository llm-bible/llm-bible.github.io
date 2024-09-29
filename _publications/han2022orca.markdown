---
layout: publication
title: ORCA Interpreting Prompted Language Models Via Locating Supporting Data Evidence In The Ocean Of Pretraining Data
authors: Han Xiaochuang, Tsvetkov Yulia
conference: "Arxiv"
year: 2022
bibkey: han2022orca
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.12600"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large pretrained language models have been performing increasingly well in a variety of downstream tasks via prompting. However it remains unclear from where the model learns the task-specific knowledge especially in a zero-shot setup. In this work we want to find evidence of the models task-specific competence from pretraining and are specifically interested in locating a very small subset of pretraining data that directly supports the model in the task. We call such a subset supporting data evidence and propose a novel method ORCA to effectively identify it by iteratively using gradient information related to the downstream task. This supporting data evidence offers interesting insights about the prompted language models in the tasks of sentiment analysis and textual entailment BERT shows a substantial reliance on BookCorpus the smaller corpus of BERTs two pretraining corpora as well as on pretraining examples that mask out synonyms to the task verbalizers.
