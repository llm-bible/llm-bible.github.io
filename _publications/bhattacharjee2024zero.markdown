---
layout: publication
title: 'Zero-shot Llm-guided Counterfactual Generation: A Case Study On NLP Model Evaluation'
authors: Amrita Bhattacharjee, Raha Moraffah, Joshua Garland, Huan Liu
conference: "Arxiv"
year: 2024
bibkey: bhattacharjee2024zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.04793'}
tags: ['Interpretability and Explainability', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Interpretability', 'Pretraining Methods']
---
With the development and proliferation of large, complex, black-box models
for solving many natural language processing (NLP) tasks, there is also an
increasing necessity of methods to stress-test these models and provide some
degree of interpretability or explainability. While counterfactual examples are
useful in this regard, automated generation of counterfactuals is a data and
resource intensive process. such methods depend on models such as pre-trained
language models that are then fine-tuned on auxiliary, often task-specific
datasets, that may be infeasible to build in practice, especially for new tasks
and data domains. Therefore, in this work we explore the possibility of
leveraging large language models (LLMs) for zero-shot counterfactual generation
in order to stress-test NLP models. We propose a structured pipeline to
facilitate this generation, and we hypothesize that the instruction-following
and textual understanding capabilities of recent LLMs can be effectively
leveraged for generating high quality counterfactuals in a zero-shot manner,
without requiring any training or fine-tuning. Through comprehensive
experiments on a variety of propreitary and open-source LLMs, along with
various downstream tasks in NLP, we explore the efficacy of LLMs as zero-shot
counterfactual generators in evaluating and explaining black-box NLP models.
