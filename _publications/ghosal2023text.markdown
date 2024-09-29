---
layout: publication
title: Text45;to45;audio Generation Using Instruction45;tuned LLM And Latent Diffusion Model
authors: Ghosal Deepanway, Majumder Navonil, Mehrish Ambuj, Poria Soujanya
conference: "Arxiv"
year: 2023
bibkey: ghosal2023text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.13731"}
tags: ['Applications', 'Merging', 'Training Techniques']
---
The immense scale of the recent large language models (LLM) allows many interesting properties such as instruction45; and chain45;of45;thought45;based fine45;tuning that has significantly improved zero45; and few45;shot performance in many natural language processing (NLP) tasks. Inspired by such successes we adopt such an instruction45;tuned LLM Flan45;T5 as the text encoder for text45;to45;audio (TTA) generation 45;45; a task where the goal is to generate an audio from its textual description. The prior works on TTA either pre45;trained a joint text45;audio encoder or used a non45;instruction45;tuned model such as T5. Consequently our latent diffusion model (LDM)45;based approach TANGO outperforms the state45;of45;the45;art AudioLDM on most metrics and stays comparable on the rest on AudioCaps test set despite training the LDM on a 63 times smaller dataset and keeping the text encoder frozen. This improvement might also be attributed to the adoption of audio pressure level45;based sound mixing for training set augmentation whereas the prior methods take a random mix.
