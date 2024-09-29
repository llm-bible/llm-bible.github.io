---
layout: publication
title: "Gradient-based Automated Iterative Recovery For Parameter-efficient Tuning"
authors: Mozes Maximilian, Bolukbasi Tolga, Yuan Ann, Liu Frederick, Thain Nithum, Dixon Lucas
conference: "Arxiv"
year: 2023
bibkey: mozes2023gradient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.06598"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Prompting', 'Responsible AI', 'Training Techniques']
---
Pretrained large language models (LLMs) are able to solve a wide variety of tasks through transfer learning. Various explainability methods have been developed to investigate their decision making process. TracIn (Pruthi et al. 2020) is one such gradient-based method which explains model inferences based on the influence of training examples. In this paper we explore the use of TracIn to improve model performance in the parameter-efficient tuning (PET) setting. We develop conversational safety classifiers via the prompt-tuning PET method and show how the unique characteristics of the PET regime enable TracIn to identify the cause for certain misclassifications by LLMs. We develop a new methodology for using gradient-based explainability techniques to improve model performance G-BAIR gradient-based automated iterative recovery. We show that G-BAIR can recover LLM performance on benchmarks after manually corrupting training labels. This suggests that influence methods like TracIn can be used to automatically perform data cleaning and introduces the potential for interactive debugging and relabeling for PET-based transfer learning methods.
