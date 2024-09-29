---
layout: publication
title: Anchored Answers Unravelling Positional Bias In Gpt-2s Multiple-choice Questions
authors: Li Ruizhe, Gao Yanjun
conference: "Arxiv"
year: 2024
bibkey: li2024anchored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03205"}
  - {name: "Code", url: "https://github.com/ruizheliUOA/Anchored_Bias_GPT2"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
Large Language Models (LLMs) such as the GPT-4 and LLaMA families have demonstrated considerable success across diverse tasks including multiple-choice questions (MCQs). However these models exhibit a positional bias particularly an even worse anchored bias in the GPT-2 family where they consistently favour the first choice A in MCQs during inference. This anchored bias challenges the integrity of GPT-2s decision-making process as it skews performance based on the position rather than the content of the choices in MCQs. In this study we utilise the mechanistic interpretability approach to identify the internal modules within GPT-2 models responsible for this bias. We focus on the Multi-Layer Perceptron (MLP) layers and attention heads using the logit lens method to trace and modify the specific value vectors that contribute to the bias. By updating these vectors within MLP and recalibrating attention patterns to neutralise the preference for the first choice A we effectively mitigate the anchored bias. Our interventions not only mitigate the bias but also improve the overall MCQ prediction accuracy for the GPT-2 family across various datasets. This work represents the first comprehensive mechanistic analysis of anchored bias in MCQs within the GPT-2 models introducing targeted minimal-intervention strategies that significantly enhance GPT2 model robustness and accuracy in MCQs. Our code is available at https://github.com/ruizheliUOA/Anchored\_Bias\_GPT2."
