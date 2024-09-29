---
layout: publication
title: HoneyBee Progressive Instruction Finetuning of Large Language Models for Materials Science
authors: Song Yu, Miret Santiago, Zhang Huan, Liu Bang
conference: "Arxiv"
year: 2023
bibkey: song2023honeybee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08511"}
  - {name: "Code", url: "https://github.com/BangLab-UdeM-Mila/NLP4MatSci-HoneyBee"}
tags: ['GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
We propose an instruction-based process for trustworthy data curation in materials science (MatSci-Instruct) which we then apply to finetune a LLaMa-based language model targeted for materials science (HoneyBee). MatSci-Instruct helps alleviate the scarcity of relevant high-quality materials science textual data available in the open literature and HoneyBee is the first billion-parameter language model specialized to materials science. In MatSci-Instruct we improve the trustworthiness of generated data by prompting multiple commercially available large language models for generation with an Instructor module (e.g. Chat-GPT) and verification from an independent Verifier module (e.g. Claude). Using MatSci-Instruct we construct a dataset of multiple tasks and measure the quality of our dataset along multiple dimensions including accuracy against known facts relevance to materials science as well as completeness and reasonableness of the data. Moreover we iteratively generate more targeted instructions and instruction-data in a finetuning-evaluation-feedback loop leading to progressively better performance for our finetuned HoneyBee models. Our evaluation on the MatSci-NLP benchmark shows HoneyBees outperformance of existing language models on materials science tasks and iterative improvement in successive stages of instruction-data refinement. We study the quality of HoneyBees language modeling through automatic evaluation and analyze case studies to further understand the models capabilities and limitations. Our code and relevant datasets are publicly available at url https://github.com/BangLab-UdeM-Mila/NLP4MatSci-HoneyBee.
