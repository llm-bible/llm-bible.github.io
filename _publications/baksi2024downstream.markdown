---
layout: publication
title: Downstream Bias Mitigation Is All You Need
authors: Baksi Arkadeep, Singh Rahul, Joshi Tarun
conference: "Arxiv"
year: 2024
bibkey: baksi2024downstream
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00612"}
tags: ['Applications', 'Bias Mitigation', 'Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The advent of transformer45;based architectures and large language models (LLMs) have significantly advanced the performance of natural language processing (NLP) models. Since these LLMs are trained on huge corpuses of data from the web and other sources there has been a major concern about harmful prejudices that may potentially be transferred from the data. In many applications these pre45;trained LLMs are fine45;tuned on task specific datasets which can further contribute to biases. This paper studies the extent of biases absorbed by LLMs during pre45;training as well as task45;specific behaviour after fine45;tuning. We found that controlled interventions on pre45;trained LLMs prior to fine45;tuning have minimal effect on lowering biases in classifiers. However the biases present in domain45;specific datasets play a much bigger role and hence mitigating them at this stage has a bigger impact. While pre45;training does matter but after the model has been pre45;trained even slight changes to co45;occurrence rates in the fine45;tuning dataset has a significant effect on the bias of the model.
