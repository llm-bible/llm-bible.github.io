---
layout: publication
title: Human-interpretable Adversarial Prompt Attack On Large Language Models With Situational Context
authors: Das Nilanjana, Raff Edward, Gaur Manas
conference: "Arxiv"
year: 2024
bibkey: das2024human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14644"}
tags: ['Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Security', 'Survey Paper']
---
Previous research on testing the vulnerabilities in Large Language Models (LLMs) using adversarial attacks has primarily focused on nonsensical prompt injections which are easily detected upon manual or automated review (e.g. via byte entropy). However the exploration of innocuous human-understandable malicious prompts augmented with adversarial injections remains limited. In this research we explore converting a nonsensical suffix attack into a sensible prompt via a situation-driven contextual re-writing. This allows us to show suffix conversion without any gradients using only LLMs to perform the attacks and thus better understand the scope of possible risks. We combine an independent meaningful adversarial insertion and situations derived from movies to check if this can trick an LLM. The situations are extracted from the IMDB dataset and prompts are defined following a few-shot chain-of-thought prompting. Our approach demonstrates that a successful situation-driven attack can be executed on both open-source and proprietary LLMs. We find that across many LLMs as few as 1 attempt produces an attack and that these attacks transfer between LLMs.
