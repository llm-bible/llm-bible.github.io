---
layout: publication
title: 'Augmenting Human-annotated Training Data With Large Language Model Generation And Distillation In Open-response Assessment'
authors: Conrad Borchers, Danielle R. Thomas, Jionghao Lin, Ralph Abboud, Kenneth R. Koedinger
conference: "Arxiv"
year: 2025
bibkey: borchers2025augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09126"}
tags: ['Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'BERT', 'Distillation']
---
Large Language Models (LLMs) like GPT-4o can help automate text
classification tasks at low cost and scale. However, there are major concerns
about the validity and reliability of LLM outputs. By contrast, human coding is
generally more reliable but expensive to procure at scale. In this study, we
propose a hybrid solution to leverage the strengths of both. We combine
human-coded data and synthetic LLM-produced data to fine-tune a classical
machine learning classifier, distilling both into a smaller BERT model. We
evaluate our method on a human-coded test set as a validity measure for LLM
output quality. In three experiments, we systematically vary LLM-generated
samples' size, variety, and consistency, informed by best practices in LLM
tuning. Our findings indicate that augmenting datasets with synthetic samples
improves classifier performance, with optimal results achieved at an 80%
synthetic to 20% human-coded data ratio. Lower temperature settings of 0.3,
corresponding to less variability in LLM generations, produced more stable
improvements but also limited model learning from augmented samples. In
contrast, higher temperature settings (0.7 and above) introduced greater
variability in performance estimates and, at times, lower performance. Hence,
LLMs may produce more uniform output that classifiers overfit to earlier or
produce more diverse output that runs the risk of deteriorating model
performance through information irrelevant to the prediction task. Filtering
out inconsistent synthetic samples did not enhance performance. We conclude
that integrating human and LLM-generated data to improve text classification
models in assessment offers a scalable solution that leverages both the
accuracy of human coding and the variety of LLM outputs.
