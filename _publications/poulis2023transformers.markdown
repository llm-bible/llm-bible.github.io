---
layout: publication
title: Transformers In The Service Of Description Logic45;based Contexts
authors: Poulis Angelos, Tsalapati Eleni, Koubarakis Manolis
conference: "Arxiv"
year: 2023
bibkey: poulis2023transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08941"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Recent advancements in transformer45;based models have initiated research interests in investigating their ability to learn to perform reasoning tasks. However most of the contexts used for this purpose are in practice very simple generated from short (fragments of) first45;order logic sentences with only a few logical operators and quantifiers. In this work we construct the natural language dataset DELTA95;D using the description logic language mathcal123;ALCQ125;. DELTA95;D contains 384K examples and increases in two dimensions i) reasoning depth and ii) linguistic complexity. In this way we systematically investigate the reasoning ability of a supervised fine45;tuned DeBERTa45;based model and of two large language models (GPT45;3.5 GPT45;4) with few45;shot prompting. Our results demonstrate that the DeBERTa45;based model can master the reasoning task and that the performance of GPTs can improve significantly even when a small number of samples is provided (9 shots). We open45;source our code and datasets.
