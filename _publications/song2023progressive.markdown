---
layout: publication
title: Honeybee Progressive Instruction Finetuning Of Large Language Models For Materials Science
authors: Song Yu, Miret Santiago, Zhang Huan, Liu Bang
conference: "Arxiv"
year: 2023
bibkey: song2023progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08511"}
  - {name: "Code", url: "https://github.com/BangLab&#45;UdeM&#45;Mila/NLP4MatSci&#45;HoneyBee&#125;"}
tags: ['GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
We propose an instruction45;based process for trustworthy data curation in materials science (MatSci45;Instruct) which we then apply to finetune a LLaMa45;based language model targeted for materials science (HoneyBee). MatSci45;Instruct helps alleviate the scarcity of relevant high45;quality materials science textual data available in the open literature and HoneyBee is the first billion45;parameter language model specialized to materials science. In MatSci45;Instruct we improve the trustworthiness of generated data by prompting multiple commercially available large language models for generation with an Instructor module (e.g. Chat45;GPT) and verification from an independent Verifier module (e.g. Claude). Using MatSci45;Instruct we construct a dataset of multiple tasks and measure the quality of our dataset along multiple dimensions including accuracy against known facts relevance to materials science as well as completeness and reasonableness of the data. Moreover we iteratively generate more targeted instructions and instruction45;data in a finetuning45;evaluation45;feedback loop leading to progressively better performance for our finetuned HoneyBee models. Our evaluation on the MatSci45;NLP benchmark shows HoneyBees outperformance of existing language models on materials science tasks and iterative improvement in successive stages of instruction45;data refinement. We study the quality of HoneyBees language modeling through automatic evaluation and analyze case studies to further understand the models capabilities and limitations. Our code and relevant datasets are publicly available at url123;https://github.com/BangLab&#45;UdeM&#45;Mila/NLP4MatSci&#45;HoneyBee&#125;.
