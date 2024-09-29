---
layout: publication
title: Promptfix: Few-shot Backdoor Removal Via Adversarial Prompt Tuning
authors: Zhang Tianrong, Xi Zhaohan, Wang Ting, Mitra Prasenjit, Chen Jinghui
conference: "Arxiv"
year: 2024
bibkey: zhang2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04478"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
Pre-trained language models (PLMs) have attracted enormous attention over the past few years with their unparalleled performances. Meanwhile the soaring cost to train PLMs as well as their amazing generalizability have jointly contributed to few-shot fine-tuning and prompting as the most popular training paradigms for natural language processing (NLP) models. Nevertheless existing studies have shown that these NLP models can be backdoored such that model behavior is manipulated when trigger tokens are presented. In this paper we propose PromptFix a novel backdoor mitigation strategy for NLP models via adversarial prompt-tuning in few-shot settings. Unlike existing NLP backdoor removal methods which rely on accurate trigger inversion and subsequent model fine-tuning PromptFix keeps the model parameters intact and only utilizes two extra sets of soft tokens which approximate the trigger and counteract it respectively. The use of soft tokens and adversarial optimization eliminates the need to enumerate possible backdoor configurations and enables an adaptive balance between trigger finding and preservation of performance. Experiments with various backdoor attacks validate the effectiveness of the proposed method and the performances when domain shift is present further shows PromptFixs applicability to models pretrained on unknown data source which is the common case in prompt tuning scenarios.
