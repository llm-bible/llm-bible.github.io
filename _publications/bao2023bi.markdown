---
layout: publication
title: 'A Bi-step Grounding Paradigm For Large Language Models In Recommendation Systems'
authors: Keqin Bao, Jizhi Zhang, Wenjie Wang, Yang Zhang, Zhengyi Yang, Yancheng Luo, Chong Chen, Fuli Feng, Qi Tian
conference: "Arxiv"
year: 2023
bibkey: bao2023bi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.08434'}
  - {name: "Code", url: 'https://github.com/SAI990323/Grounding4Rec'}
tags: ['Has Code', 'Few-Shot', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
As the focus on Large Language Models (LLMs) in the field of recommendation
intensifies, the optimization of LLMs for recommendation purposes (referred to
as LLM4Rec) assumes a crucial role in augmenting their effectiveness in
providing recommendations. However, existing approaches for LLM4Rec often
assess performance using restricted sets of candidates, which may not
accurately reflect the models' overall ranking capabilities. In this paper, our
objective is to investigate the comprehensive ranking capacity of LLMs and
propose a two-step grounding framework known as BIGRec (Bi-step Grounding
Paradigm for Recommendation). It initially grounds LLMs to the recommendation
space by fine-tuning them to generate meaningful tokens for items and
subsequently identifies appropriate actual items that correspond to the
generated tokens. By conducting extensive experiments on two datasets, we
substantiate the superior performance, capacity for handling few-shot
scenarios, and versatility across multiple domains exhibited by BIGRec.
Furthermore, we observe that the marginal benefits derived from increasing the
quantity of training samples are modest for BIGRec, implying that LLMs possess
the limited capability to assimilate statistical information, such as
popularity and collaborative filtering, due to their robust semantic priors.
These findings also underline the efficacy of integrating diverse statistical
information into the LLM4Rec framework, thereby pointing towards a potential
avenue for future research. Our code and data are available at
https://github.com/SAI990323/Grounding4Rec.
