---
layout: publication
title: 'ROBBIE: Robust Bias Evaluation Of Large Generative Language Models'
authors: David Esiobu, Xiaoqing Tan, Saghar Hosseini, Megan Ung, Yuchen Zhang, Jude Fernandes, Jane Dwivedi-yu, Eleonora Presani, Adina Williams, Eric Michael Smith
conference: "Arxiv"
year: 2023
bibkey: esiobu2023robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.18140'}
tags: ['RAG', 'Pre-Training', 'Fairness', 'Training Techniques', 'Tools', 'Prompting', 'Survey Paper', 'Bias Mitigation', 'Ethics and Bias']
---
As generative large language models (LLMs) grow more performant and
prevalent, we must develop comprehensive enough tools to measure and improve
their fairness. Different prompt-based datasets can be used to measure social
bias across multiple text domains and demographic axes, meaning that testing
LLMs on more datasets can potentially help us characterize their biases more
fully, and better ensure equal and equitable treatment of marginalized
demographic groups. In this work, our focus is two-fold:
  (1) Benchmarking: a comparison of 6 different prompt-based bias and toxicity
metrics across 12 demographic axes and 5 families of generative LLMs. Out of
those 6 metrics, AdvPromptSet and HolisticBiasR are novel datasets proposed in
the paper. The comparison of those benchmarks gives us insights about the bias
and toxicity of the compared models. Therefore, we explore the frequency of
demographic terms in common LLM pre-training corpora and how this may relate to
model biases.
  (2) Mitigation: we conduct a comprehensive study of how well 3 bias/toxicity
mitigation techniques perform across our suite of measurements. ROBBIE aims to
provide insights for practitioners while deploying a model, emphasizing the
need to not only measure potential harms, but also understand how they arise by
characterizing the data, mitigate harms once found, and balance any trade-offs.
We open-source our analysis code in hopes of encouraging broader measurements
of bias in future LLMs.
