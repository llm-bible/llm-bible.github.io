---
layout: publication
title: Llama45;excitor General Instruction Tuning Via Indirect Feature Interaction
authors: Zou Bo, Yang Chao, Qiao Yu, Quan Chengbin, Zhao Youjian
conference: "Arxiv"
year: 2024
bibkey: zou2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00913"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Existing methods to fine45;tune LLMs like Adapter Prefix45;tuning and LoRA which introduce extra modules or additional input sequences to inject new skills or knowledge may compromise the innate abilities of LLMs. In this paper we propose LLaMA45;Excitor a lightweight method that stimulates the LLMs potential to better follow instructions by gradually paying more attention to worthwhile information. Specifically the LLaMA45;Excitor does not directly change the intermediate hidden state during the self45;attention calculation of the transformer structure. We designed the Excitor block as a bypass module for the similarity score computation in LLMs self45;attention to reconstruct keys and change the importance of values by learnable prompts. LLaMA45;Excitor ensures a self45;adaptive allocation of additional attention to input instructions thus effectively preserving LLMs pre45;trained knowledge when fine45;tuning LLMs on low45;quality instruction45;following datasets. Furthermore we unify the modeling of multi45;modal tuning and language45;only tuning extending LLaMA45;Excitor to a powerful visual instruction follower without the need for complex multi45;modal alignment. Our proposed approach is evaluated in language45;only and multi45;modal tuning experimental scenarios. Notably LLaMA45;Excitor is the only method that maintains basic capabilities while achieving a significant improvement (+637;) on the MMLU benchmark. In the visual instruction tuning we achieve a new state45;of45;the45;art image captioning performance of 157.5 CIDEr on MSCOCO and a comparable performance (88.3937;) on ScienceQA to cutting45;edge models with more parameters and extensive vision45;language pertaining.
