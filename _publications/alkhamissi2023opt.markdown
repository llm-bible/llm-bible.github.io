---
layout: publication
title: OPT-R Exploring the Role of Explanations in Finetuning and Prompting for Reasoning Skills of Large Language Models
authors: Alkhamissi Badr, Verma Siddharth, Yu Ping, Jin Zhijing, Celikyilmaz Asli, Diab Mona
conference: "Arxiv"
year: 2023
bibkey: alkhamissi2023opt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12001"}
tags: ['Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
In this paper we conduct a thorough investigation into the reasoning capabilities of Large Language Models (LLMs) focusing specifically on the Open Pretrained Transformers (OPT) models as a representative of such models. Our study entails finetuning three different sizes of OPT on a carefully curated reasoning corpus resulting in two sets of finetuned models OPT-R finetuned without explanations and OPT-RE finetuned with explanations. We then evaluate all models on 57 out-of-domain tasks drawn from the SUPER-NATURALINSTRUCTIONS benchmark covering 26 distinct reasoning skills utilizing three prompting techniques. Through a comprehensive grid of 27 configurations and 6156 test evaluations we investigate the dimensions of finetuning prompting and scale to understand the role of explanations on different reasoning skills. Our findings reveal that having explanations in the fewshot exemplar has no significant impact on the models performance when the model is finetuned while positively affecting the non-finetuned counterpart. Moreover we observe a slight yet consistent increase in classification accuracy as we incorporate explanations during prompting and finetuning respectively. Finally we offer insights on which skills benefit the most from incorporating explanations during finetuning and prompting such as Numerical (+20.4) and Analogical (+13.9) reasoning as well as skills that exhibit negligible or negative effects.
