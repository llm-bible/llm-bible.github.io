---
layout: publication
title: 'A Scaling Law For Token Efficiency In LLM Fine-tuning Under Fixed Compute Budgets'
authors: Ryan Lagasse, Aidan Kierans, Avijit Ghosh, Shiri Dori-hacohen
conference: "Arxiv"
year: 2025
bibkey: lagasse2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06150'}
tags: ['Large-Scale Training', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Scaling Laws', 'Model Architecture', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
We introduce a scaling law for fine-tuning large language models (LLMs) under fixed compute budgets that explicitly accounts for data composition. Conventional approaches measure training data solely by total tokens, yet the number of examples and their average token length -- what we term *dataset volume* -- play a decisive role in model performance. Our formulation is tuned following established procedures. Experiments on the BRICC dataset \cite\{salavati2024reducing\} and subsets of the MMLU dataset \cite\{hendrycks2021measuringmassivemultitasklanguage\}, evaluated under multiple subsampling strategies, reveal that data composition significantly affects token efficiency. These results motivate refined scaling laws for practical LLM fine-tuning in resource-constrained settings.
