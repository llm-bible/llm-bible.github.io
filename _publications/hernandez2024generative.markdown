---
layout: publication
title: Generative Visual Instruction Tuning
authors: Hernandez Jefferson, Villegas Ruben, Ordonez Vicente
conference: "Arxiv"
year: 2024
bibkey: hernandez2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11262"}
tags: ['GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
We propose to use machine45;generated instruction45;following data to improve the zero45;shot capabilities of a large multimodal model with additional support for generative and image editing tasks. We achieve this by curating a new multimodal instruction45;following set using GPT45;4V and existing datasets for image generation and editing. Using this instruction set and the existing LLaVA45;Finetune instruction set for visual understanding tasks we produce GenLLaVA a Generative Large Language and Visual Assistant. GenLLaVA is built through a strategy that combines three types of large pre45;trained models through instruction finetuning LLaMA for language modeling SigLIP for image45;text matching and StableDiffusion for text45;to45;image generation. Our model demonstrates visual understanding capabilities on par with LLaVA and additionally demonstrates competitive results with native multimodal models such as Unified45;IO 2 paving the way for building advanced general45;purpose visual assistants by effectively re45;using existing multimodal models. We open45;source our dataset codebase and model checkpoints to foster further research and application in this domain.
