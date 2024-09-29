---
layout: publication
title: Entity Matching Using Large Language Models
authors: Peeters Ralph, Bizer Christian
conference: "Arxiv"
year: 2023
bibkey: peeters2023entity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11244"}
tags: ['BERT', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Entity Matching is the task of deciding whether two entity descriptions refer to the same real45;world entity and is a central step in most data integration pipelines. Many state45;of45;the45;art entity matching methods rely on pre45;trained language models (PLMs) such as BERT or RoBERTa. Two major drawbacks of these models for entity matching are that (i) the models require significant amounts of task45;specific training data and (ii) the fine45;tuned models are not robust concerning out45;of45;distribution entities. This paper investigates using generative large language models (LLMs) as a less task45;specific training data45;dependent and more robust alternative to PLM45;based matchers. Our study covers hosted and open45;source LLMs which can be run locally. We evaluate these models in a zero45;shot scenario and a scenario where task45;specific training data is available. We compare different prompt designs and the prompt sensitivity of the models and show that there is no single best prompt but needs to be tuned for each model/dataset combination. We further investigate (i) the selection of in45;context demonstrations (ii) the generation of matching rules as well as (iii) fine45;tuning a hosted LLM using the same pool of training data. Our experiments show that the best LLMs require no or only a few training examples to perform similarly to PLMs that were fine45;tuned using thousands of examples. LLM45;based matchers further exhibit higher robustness to unseen entities. We show that GPT4 can generate structured explanations for matching decisions. The model can automatically identify potential causes of matching errors by analyzing explanations of wrong decisions. We demonstrate that the model can generate meaningful textual descriptions of the identified error classes which can help data engineers improve entity matching pipelines.
