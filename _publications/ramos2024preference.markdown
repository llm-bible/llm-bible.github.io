---
layout: publication
title: "Preference Distillation For Personalized Generative Recommendation"
authors: Ramos Jerome, Wu Bin, Lipani Aldo
conference: "Arxiv"
year: 2024
bibkey: ramos2024preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05033"}
tags: ['Distillation', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Prompting', 'Reinforcement Learning']
---
Recently researchers have investigated the capabilities of Large Language Models (LLMs) for generative recommender systems. Existing LLM-based recommender models are trained by adding user and item IDs to a discrete prompt template. However the disconnect between IDs and natural language makes it difficult for the LLM to learn the relationship between users. To address this issue we propose a PErsonAlized PrOmpt Distillation (PeaPOD) approach to distill user preferences as personalized soft prompts. Considering the complexities of user preferences in the real world we maintain a shared set of learnable prompts that are dynamically weighted based on the users interests to construct the user-personalized prompt in a compositional manner. Experimental results on three real-world datasets demonstrate the effectiveness of our PeaPOD model on sequential recommendation top-n recommendation and explanation generation tasks.
