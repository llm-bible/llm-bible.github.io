---
layout: publication
title: 'Improving Text-to-image Consistency Via Automatic Prompt Optimization'
authors: Mañas Oscar, Astolfi Pietro, Hall Melissa, Ross Candace, Urbanek Jack, Williams Adina, Agrawal Aishwarya, Romero-soriano Adriana, Drozdzal Michal
conference: "Arxiv"
year: 2024
bibkey: mañas2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17804"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
'Impressive advances in text-to-image (T2I) generative models have yielded a plethora of high performing models which are able to generate aesthetically appealing, photorealistic images. Despite the progress, these models still struggle to produce images that are consistent with the input prompt, oftentimes failing to capture object quantities, relations and attributes properly. Existing solutions to improve prompt-image consistency suffer from the following challenges: (1) they oftentimes require model fine-tuning, (2) they only focus on nearby prompt samples, and (3) they are affected by unfavorable trade-offs among image quality, representation diversity, and prompt-image consistency. In this paper, we address these challenges and introduce a T2I optimization-by-prompting framework, OPT2I, which leverages a large language model (LLM) to improve prompt-image consistency in T2I models. Our framework starts from a user prompt and iteratively generates revised prompts with the goal of maximizing a consistency score. Our extensive validation on two datasets, MSCOCO and PartiPrompts, shows that OPT2I can boost the initial consistency score by up to 24.9&#37; in terms of DSG score while preserving the FID and increasing the recall between generated and real data. Our work paves the way toward building more reliable and robust T2I systems by harnessing the power of LLMs.'
