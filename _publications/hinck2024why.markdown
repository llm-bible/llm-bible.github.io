---
layout: publication
title: Why Do Llava Vision45;language Models Reply To Images In English
authors: Hinck Musashi, Holtermann Carolin, Olson Matthew Lyle, Schneider Florian, Yu Sungduk, Bhiwandiwalla Anahita, Lauscher Anne, Tseng Shaoyen, Lal Vasudev
conference: "Arxiv"
year: 2024
bibkey: hinck2024why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02333"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Multimodal Models']
---
We uncover a surprising multilingual bias occurring in a popular class of multimodal vision45;language models (VLMs). Including an image in the query to a LLaVA45;style VLM significantly increases the likelihood of the model returning an English response regardless of the language of the query. This paper investigates the causes of this loss with a two45;pronged approach that combines extensive ablation of the design space with a mechanistic analysis of the models internal representations of image and text inputs. Both approaches indicate that the issue stems in the language modelling component of the LLaVA model. Statistically we find that switching the language backbone for a bilingual language model has the strongest effect on reducing this error. Mechanistically we provide compelling evidence that visual inputs are not mapped to a similar space as text ones and that intervening on intermediary attention layers can reduce this bias. Our findings provide important insights to researchers and engineers seeking to understand the crossover between multimodal and multilingual spaces and contribute to the goal of developing capable and inclusive VLMs for non45;English contexts.
