---
layout: publication
title: "Competence-based Analysis Of Language Models"
authors: Davies Adam, Jiang Jize, Zhai Chengxiang
conference: "Arxiv"
year: 2023
bibkey: davies2023competence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.00333"}
tags: ['Pretraining Methods', 'Prompting', 'Security', 'Tools', 'Training Techniques']
---
Despite the recent successes of large pretrained neural language models (LLMs) comparatively little is known about the representations of linguistic structure they learn during pretraining which can lead to unexpected behaviors in response to prompt variation or distribution shift. To better understand these models and behaviors we introduce a general model analysis framework to study LLMs with respect to their representation and use of human-interpretable linguistic properties. Our framework CALM (Competence-based Analysis of Language Models) is designed to investigate LLM competence in the context of specific tasks by intervening on models internal representations of different linguistic properties using causal probing and measuring models alignment under these interventions with a given ground-truth causal model of the task. We also develop a new approach for performing causal probing interventions using gradient-based adversarial attacks which can target a broader range of properties and representations than prior techniques. Finally we carry out a case study of CALM using these interventions to analyze and compare LLM competence across a variety of lexical inference tasks showing that CALM can be used to explain and predict behaviors across these tasks.
