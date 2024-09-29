---
layout: publication
title: Gotcha! Don''t Trick Me With Unanswerable Questions! Self-aligning Large Language Models For Responding To Unknown Questions
authors: Deng Yang, Zhao Yong, Li Moxin, Ng See-kiong, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: deng2024trick
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15062"}
tags: ['Fine Tuning', 'Interpretability And Explainability', 'Pretraining Methods', 'Training Techniques']
---
Despite the remarkable abilities of Large Language Models (LLMs) to answer questions they often display a considerable level of overconfidence even when the question does not have a definitive answer. To avoid providing hallucinated answers to these unknown questions existing studies typically investigate approaches to refusing to answer these questions. In this work we propose a novel and scalable self-alignment method to utilize the LLM itself to enhance its response-ability to different types of unknown questions being capable of not only refusing to answer but also providing explanation to the unanswerability of unknown questions. Specifically the Self-Align method first employ a two-stage class-aware self-augmentation approach to generate a large amount of unknown question-response data. Then we conduct disparity-driven self-curation to select qualified data for fine-tuning the LLM itself for aligning the responses to unknown questions as desired. Experimental results on two datasets across four types of unknown questions validate the superiority of the Self-Align method over existing baselines in terms of three types of task formulation.
