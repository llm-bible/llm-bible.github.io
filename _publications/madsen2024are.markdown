---
layout: publication
title: Are Self45;explanations From Large Language Models Faithful
authors: Madsen Andreas, Chandar Sarath, Reddy Siva
conference: "Arxiv"
year: 2024
bibkey: madsen2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07927"}
tags: ['Interpretability And Explainability', 'Reinforcement Learning', 'Tools']
---
Instruction45;tuned Large Language Models (LLMs) excel at many tasks and will even explain their reasoning so45;called self45;explanations. However convincing and wrong self45;explanations can lead to unsupported confidence in LLMs thus increasing risk. Therefore its important to measure if self45;explanations truly reflect the models behavior. Such a measure is called interpretability45;faithfulness and is challenging to perform since the ground truth is inaccessible and many LLMs only have an inference API. To address this we propose employing self45;consistency checks to measure faithfulness. For example if an LLM says a set of words is important for making a prediction then it should not be able to make its prediction without these words. While self45;consistency checks are a common approach to faithfulness they have not previously been successfully applied to LLM self45;explanations for counterfactual feature attribution and redaction explanations. Our results demonstrate that faithfulness is explanation model and task45;dependent showing self45;explanations should not be trusted in general. For example with sentiment classification counterfactuals are more faithful for Llama2 feature attribution for Mistral and redaction for Falcon 40B.
