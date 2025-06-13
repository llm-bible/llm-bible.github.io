---
layout: publication
title: 'Entity Matching Using Large Language Models'
authors: Ralph Peeters, Aaron Steiner, Christian Bizer
conference: "Arxiv"
year: 2023
bibkey: peeters2023entity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11244"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting']
---
Entity matching is the task of deciding whether two entity descriptions refer
to the same real-world entity. Entity matching is a central step in most data
integration pipelines. Many state-of-the-art entity matching methods rely on
pre-trained language models (PLMs) such as BERT or RoBERTa. Two major drawbacks
of these models for entity matching are that (i) the models require significant
amounts of task-specific training data and (ii) the fine-tuned models are not
robust concerning out-of-distribution entities. This paper investigates using
generative large language models (LLMs) as a less task-specific training
data-dependent and more robust alternative to PLM-based matchers. The study
covers hosted and open-source LLMs which can be run locally. We evaluate these
models in a zero-shot scenario and a scenario where task-specific training data
is available. We compare different prompt designs and the prompt sensitivity of
the models. We show that there is no single best prompt but that the prompt
needs to be tuned for each model/dataset combination. We further investigate
(i) the selection of in-context demonstrations, (ii) the generation of matching
rules, as well as (iii) fine-tuning LLMs using the same pool of training data.
Our experiments show that the best LLMs require no or only a few training
examples to perform comparably to PLMs that were fine-tuned using thousands of
examples. LLM-based matchers further exhibit higher robustness to unseen
entities. We show that GPT4 can generate structured explanations for matching
decisions and can automatically identify potential causes of matching errors by
analyzing explanations of wrong decisions. We demonstrate that the model can
generate meaningful textual descriptions of the identified error classes, which
can help data engineers to improve entity matching pipelines.
