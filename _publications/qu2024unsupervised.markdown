---
layout: publication
title: Unsupervised Distractor Generation Via Large Language Model Distilling And Counterfactual Contrastive Decoding
authors: Qu Fanyi, Sun Hao, Wu Yunfang
conference: "Arxiv"
year: 2024
bibkey: qu2024unsupervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01306"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Within the context of reading comprehension the task of Distractor Generation (DG) aims to generate several incorrect options to confuse readers. Traditional supervised methods for DG rely heavily on expensive human45;annotated distractor labels. In this paper we propose an unsupervised DG framework leveraging Large Language Models (LLMs) as cost45;effective annotators to enhance the DG capability of smaller student models. Specially to perform knowledge distilling we propose a dual task training strategy that integrates pseudo distractors from LLMs and the original answer in45;formation as the objective targets with a two45;stage training process. Moreover we devise a counterfactual contrastive decoding mechanism for increasing the distracting capability of the DG model. Experiments show that our unsupervised generation method with Bart45;base greatly surpasses GPT45;3.545;turbo performance with only 200 times fewer model parameters. Our proposed unsupervised DG method offers a cost45;effective framework for practical reading comprehension applications without the need of laborious distractor annotation and costly large45;size models
