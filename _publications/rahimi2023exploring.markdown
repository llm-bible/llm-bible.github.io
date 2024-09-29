---
layout: publication
title: Exploring The Effectiveness Of GPT Models In Test-taking: A Case Study Of The Driver's License Knowledge Test
authors: Rahimi Saba, Balch Tucker, Veloso Manuela
conference: "Arxiv"
year: 2023
bibkey: rahimi2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11827"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
Large language models such as Open AIs Generative Pre-trained Transformer (GPT) models are proficient at answering questions but their knowledge is confined to the information present in their training data. This limitation renders them ineffective when confronted with questions about recent developments or non-public documents. Our research proposes a method that enables GPT models to answer questions by employing context from an information source not previously included in their training data. The methodology includes preprocessing of contextual information the embedding of contexts and queries constructing prompt through the integration of context embeddings and generating answers using GPT models. We applied this method in a controlled test scenario using the California Drivers Handbook as the information source. The GPT-3 model achieved a 9637; passing score on a set of 50 sample driving knowledge test questions. In contrast without context the models passing score fell to 8237;. However the model still fails to answer some questions correctly even with providing library of context highlighting room for improvement. The research also examined the impact of prompt length and context format on the models performance. Overall the study provides insights into the limitations and potential improvements for GPT models in question-answering tasks.
