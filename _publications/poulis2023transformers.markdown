---
layout: publication
title: Transformers in the Service of Description Logic-based Contexts
authors: Poulis Angelos, Tsalapati Eleni, Koubarakis Manolis
conference: "Arxiv"
year: 2023
bibkey: poulis2023transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08941"}
tags: ['ARXIV', 'GPT', 'Model Architecture', 'Prompt', 'Supervised', 'Tools', 'Transformer']
---
Recent advancements in transformer-based models have initiated research interests in investigating their ability to learn to perform reasoning tasks. However most of the contexts used for this purpose are in practice very simple generated from short (fragments of) first-order logic sentences with only a few logical operators and quantifiers. In this work we construct the natural language dataset DELTA_D using the description logic language . DELTA_D contains 384K examples and increases in two dimensions i) reasoning depth and ii) linguistic complexity. In this way we systematically investigate the reasoning ability of a supervised fine-tuned DeBERTa-based model and of two large language models (GPT-3.5 GPT-4) with few-shot prompting. Our results demonstrate that the DeBERTa-based model can master the reasoning task and that the performance of GPTs can improve significantly even when a small number of samples is provided (9 shots). We open-source our code and datasets.
