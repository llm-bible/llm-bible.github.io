---
layout: publication
title: Learning to Predict Concept Ordering for Common Sense Generation
authors: Zhang Tianhui, Bollegala Danushka, Peng Bei
conference: "Arxiv"
year: 2023
bibkey: zhang2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06363"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
Prior work has shown that the ordering in which concepts are shown to a commonsense generator plays an important role affecting the quality of the generated sentence. However it remains a challenge to determine the optimal ordering of a given set of concepts such that a natural sentence covering all the concepts could be generated from a pretrained generator. To understand the relationship between the ordering of the input concepts and the quality of the generated sentences we conduct a systematic study considering multiple language models (LMs) and concept ordering strategies. We find that BART-large model consistently outperforms all other LMs considered in this study when fine-tuned using the ordering of concepts as they appear in CommonGen training data as measured using multiple evaluation metrics. Moreover the larger GPT3-based large language models (LLMs) variants do not necessarily outperform much smaller LMs on this task even when fine-tuned on task-specific training data. Interestingly human annotators significantly reorder input concept sets when manually writing sentences covering those concepts and this ordering provides the best sentence generations independently of the LM used for the generation outperforming a probabilistic concept ordering baseline
