---
layout: publication
title: 'Retrieval-reasoning Large Language Model-based Synthetic Clinical Trial Generation'
authors: Zerui Xu, Fang Wu, Yuanyuan Zhang, Yue Zhao
conference: "Arxiv"
year: 2024
bibkey: xu2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12476"}
  - {name: "Code", url: "https://anonymous.4open.science/r/Retrieval_Reasoning_Clinical_Trial_Generation-3EC4"}
tags: ['Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Machine learning (ML) exhibits promise in the clinical domain. However, it is
constrained by data scarcity and ethical considerations, as the generation of
clinical trials presents significant challenges due to stringent privacy
regulations, high costs, and the extended duration required for conducting
studies with human participants. Despite the advancements of large language
models (LLMs) in general generation tasks, their potential in facilitating the
generation of synthetic clinical trials is under-explored. To address this gap,
we introduce a novel Retrieval-Reasoning few-shot framework that leverages LLMs
to generate artificial yet realistic and diverse clinical trials with binary
success/failure labels. Experiments conducted on real clinical trials from the
\url\{ClinicalTrials.gov\} database demonstrate that our synthetic data can
effectively augment real datasets. Furthermore, by fine-tuning a pre-trained
model as a binary classifier on synthetic clinical trial datasets, we
demonstrate that this augmentation enhances model training for downstream tasks
such as trial outcome prediction. Our findings suggest that LLMs for synthetic
clinical trial generation hold promise for accelerating clinical research and
upholding ethical standards for patient privacy. The code is publicly available
at
https://anonymous.4open.science/r/Retrieval_Reasoning_Clinical_Trial_Generation-3EC4.
