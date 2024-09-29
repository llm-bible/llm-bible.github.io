---
layout: publication
title: "Learning To Prompt With Text Only Supervision For Vision-language Models"
authors: Khattak Muhammad Uzair, Naeem Muhammad Ferjad, Naseer Muzammal, Van Gool Luc, Tombari Federico
conference: "Arxiv"
year: 2024
bibkey: khattak2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02418"}
  - {name: "Code", url: "https://github.com/muzairkhattak/ProText"}
tags: ['Has Code', 'Multimodal Models', 'Prompting', 'Training Techniques']
---
Foundational vision-language models such as CLIP are becoming a new paradigm in vision due to their excellent generalization abilities. However adapting these models for downstream tasks while maintaining their generalization remains a challenge. In literature one branch of methods adapts CLIP by learning prompts using visual information. While effective most of these works require labeled data which is not practical and often struggle to generalize towards new datasets due to over-fitting on the source data. An alternative approach resorts to training-free methods by generating class descriptions from large language models (LLMs) and perform prompt ensembling. However these methods often generate class specific prompts that cannot be transferred to other classes which incur higher costs by generating LLM descriptions for each class separately. In this work we propose to combine the strengths of these both streams of methods by learning prompts using only text data derived from LLMs. As supervised training of prompts is not trivial due to absence of images we develop a training approach that allows prompts to extract rich contextual knowledge from LLM data. Moreover with LLM contextual data mapped within the learned prompts it enables zero-shot transfer of prompts to new classes and datasets potentially cutting the LLM prompt engineering cost. To the best of our knowledge this is the first work that learns generalized prompts using text only data. We perform extensive evaluations on 4 benchmarks where our method improves over prior ensembling works while being competitive to those utilizing labeled images. Our code and pre-trained models are available at https://github.com/muzairkhattak/ProText."
