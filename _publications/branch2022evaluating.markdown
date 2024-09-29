---
layout: publication
title: 'Evaluating The Susceptibility Of Pre-trained Language Models Via Handcrafted Adversarial Examples'
authors: Branch Hezekiah J., Cefalu Jonathan Rodriguez, Mchugh Jeremy, Hujer Leyla, Bahl Aditya, Iglesias Daniel Del Castillo, Heichman Ron, Darwishi Ramesh
conference: "Arxiv"
year: 2022
bibkey: branch2022evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.02128"}
tags: ['BERT', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques', 'Transformer']
---
Recent advances in the development of large language models have resulted in public access to state-of-the-art pre-trained language models (PLMs) including Generative Pre-trained Transformer 3 (GPT-3) and Bidirectional Encoder Representations from Transformers (BERT). However evaluations of PLMs in practice have shown their susceptibility to adversarial attacks during the training and fine-tuning stages of development. Such attacks can result in erroneous outputs model-generated hate speech and the exposure of users sensitive information. While existing research has focused on adversarial attacks during either the training or the fine-tuning of PLMs there is a deficit of information on attacks made between these two development phases. In this work we highlight a major security vulnerability in the public release of GPT-3 and further investigate this vulnerability in other state-of-the-art PLMs. We restrict our work to pre-trained models that have not undergone fine-tuning. Further we underscore token distance-minimized perturbations as an effective adversarial approach bypassing both supervised and unsupervised quality measures. Following this approach we observe a significant decrease in text classification quality when evaluating for semantic similarity.
