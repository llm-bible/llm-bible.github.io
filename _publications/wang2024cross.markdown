---
layout: publication
title: Cross45;refine Improving Natural Language Explanation Generation By Learning In Tandem
authors: Wang Qianli, Anikina Tatiana, Feldhus Nils, Ostermann Simon, Möller Sebastian, Schmitt Vera
conference: "Arxiv"
year: 2024
bibkey: wang2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07123"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Natural language explanations (NLEs) are vital for elucidating the reasoning behind large language model (LLM) decisions. Many techniques have been developed to generate NLEs using LLMs. However like humans LLMs might not always produce optimal NLEs on first attempt. Inspired by human learning processes we introduce Cross45;Refine which employs role modeling by deploying two LLMs as generator and critic respectively. The generator outputs a first NLE and then refines this initial explanation using feedback and suggestions provided by the critic. Cross45;Refine does not require any supervised training data or additional training. We validate Cross45;Refine across three NLP tasks using three state45;of45;the45;art open45;source LLMs through automatic and human evaluation. We select Self45;Refine (Madaan et al. 2023) as the baseline which only utilizes self45;feedback to refine the explanations. Our findings from automatic evaluation and a user study indicate that Cross45;Refine outperforms Self45;Refine. Meanwhile Cross45;Refine can perform effectively with less powerful LLMs whereas Self45;Refine only yields strong results with ChatGPT. Additionally we conduct an ablation study to assess the importance of feedback and suggestions. Both of them play an important role in refining explanations. We further evaluate Cross45;Refine on a bilingual dataset in English and German.
