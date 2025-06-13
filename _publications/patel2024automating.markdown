---
layout: publication
title: 'Automating Code Adaptation For Mlops -- A Benchmarking Study On Llms'
authors: Harsh Patel, Buvaneswari A. Ramanan, Manzoor A. Khan, Thomas Williams, Brian Friedman, Lawrence Drabeck
conference: "Arxiv"
year: 2024
bibkey: patel2024automating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06835"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Ethics and Bias']
---
This paper explores the possibilities of the current generation of Large
Language Models for incorporating Machine Learning Operations (MLOps)
functionalities into ML training code bases. We evaluate the performance of
OpenAI (gpt-3.5-turbo) and WizardCoder (open-source, 15B parameters) models on
the automated accomplishment of various MLOps functionalities in different
settings. We perform a benchmarking study that assesses the ability of these
models to: (1) adapt existing code samples (Inlining) with component-specific
MLOps functionality such as MLflow and Weights & Biases for experiment
tracking, Optuna for hyperparameter optimization etc., and (2) perform the task
of Translation from one component of an MLOps functionality to another, e.g.,
translating existing GitPython library based version control code to Data
Version Control library based. We also propose three different approaches that
involve teaching LLMs to comprehend the API documentation of the components as
a reference while accomplishing the Translation tasks. In our evaluations, the
gpt-3.5-turbo model significantly outperforms WizardCoder by achieving
impressive Pass@3 accuracy in model optimization (55% compared to 0% by
WizardCoder), experiment tracking (100%, compared to 62.5% by WizardCoder),
model registration (92% compared to 42% by WizardCoder) and hyperparameter
optimization (83% compared to 58% by WizardCoder) on average, in their best
possible settings, showcasing its superior code adaptability performance in
complex MLOps tasks.
