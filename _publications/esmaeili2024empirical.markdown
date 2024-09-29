---
layout: publication
title: Empirical Studies of Parameter Efficient Methods for Large Language Models of Code and Knowledge Transfer to R
authors: Esmaeili Amirreza, Saberi Iman, Fard Fatemeh H.
conference: "Arxiv"
year: 2024
bibkey: esmaeili2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01553"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recently Large Langauge Models (LLMs) have gained a lot of attention in the Software Engineering (SE) community. LLMs or their variants pre-trained on code are used for many SE tasks. A main approach for adapting LLMs to the downstream task is to fine-tune the models. However with having billions-parameters-LLMs fine-tuning the models is not practical. An alternative approach is using Parameter Efficient Fine Tuning (PEFT) in which the model parameters are frozen and only a few added parameters are trained. Though the LLMs are used for programming languages such as Python and Java widely their capability for low-resource languages is limited. In this work we empirically study PEFT methods LoRA and Compacter on CodeT5 and CodeLlama. We will assess their performance compared to fully fine-tuned models whether they can be used for knowledge transfer from natural language models to code (using T5 and Llama models) and their ability to adapt the learned knowledge to an unseen language. For the unseen language we aim to study R as it has a wide community. The adaptability with less computational costs makes LLMs accessible in scenarios where heavy computational resources are not available. Moreover studying R opens new opportunities for using LLMs for other languages. We anticipate our findings to showcase the capabilities of PEFT for code LLMs for R and reveal the improvement areas.
