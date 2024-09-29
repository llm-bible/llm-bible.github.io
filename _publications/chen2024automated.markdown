---
layout: publication
title: Automated Data Curation For Robust Language Model Fine45;tuning
authors: Chen Jiuhai, Mueller Jonas
conference: "Arxiv"
year: 2024
bibkey: chen2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12776"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models have become the de facto approach to sequence45;to45;sequence text generation tasks but for specialized tasks/domains a pretrained LLM lacks specific capabilities to produce accurate or well45;formatted responses. Supervised fine45;tuning specializes a LLM by training it on dataset of example prompts with target responses but real45;world data tends to be noisy. While many fine45;tuning algorithms exist here we consider a emph123;data45;centric AI125; perspective on LLM fine45;tuning studying how to emph123;systematically125; curate the training dataset to improve the LLM produced via emph123;any125; fine45;tuning algorithm. We introduce an automated data curation pipeline CLEAR (Confidence45;based LLM Evaluation And Rectification) for instruction tuning datasets that can be used with any LLM and fine45;tuning procedure. CLEAR estimates which training data is low45;quality and either filters or corrects it. Automatically identifying which data to filter or correct is done via LLM45;derived confidence estimates to ensure only confident modifications to the dataset. Unlike existing data curation techniques CLEAR is a comprehensive framework that can improve a dataset (and trained model outputs) without additional fine45;tuning computations. We dont assume access to a stronger LLM than the model being fine45;tuned (e.g. relying on GPT45;4 when fine45;tuning GPT45;3.5) to see whether CLEAR can meaningfully improve the capabilities of any LLM. Experiments reveal that CLEAR consistently improves the performance of fine45;tuned models across many datasets and models (like GPT45;3.5 and Llama2).
