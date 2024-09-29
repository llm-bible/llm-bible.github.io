---
layout: publication
title: DPP-Based Adversarial Prompt Searching for Lanugage Models
authors: Zhang Xu, Wan Xiaojun
conference: "Arxiv"
year: 2024
bibkey: zhang2024dpp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00292"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'Security']
---
Language models risk generating mindless and offensive content which hinders their safe deployment. Therefore it is crucial to discover and modify potential toxic outputs of pre-trained language models before deployment. In this work we elicit toxic content by automatically searching for a prompt that directs pre-trained language models towards the generation of a specific target output. The problem is challenging due to the discrete nature of textual data and the considerable computational resources required for a single forward pass of the language model. To combat these challenges we introduce Auto-regressive Selective Replacement Ascent (ASRA) a discrete optimization algorithm that selects prompts based on both quality and similarity with determinantal point process (DPP). Experimental results on six different pre-trained language models demonstrate the efficacy of ASRA for eliciting toxic content. Furthermore our analysis reveals a strong correlation between the success rate of ASRA attacks and the perplexity of target outputs while indicating limited association with the quantity of model parameters.
