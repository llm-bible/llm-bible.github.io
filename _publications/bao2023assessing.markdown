---
layout: publication
title: Assessing And Enhancing The Robustness Of Large Language Models With Task Structure Variations For Logical Reasoning
authors: Bao Qiming, Gendron Gael, Peng Alex Yuxuan, Zhong Wanjun, Tan Neset, Chen Yang, Witbrock Michael, Liu Jiamou
conference: "Arxiv"
year: 2023
bibkey: bao2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09430"}
  - {name: "Code", url: "https://github.com/Strong-AI-Lab/Logical-and-abstract-reasoning"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large language models (LLMs) such as LLaMA Alpaca Vicuna GPT-3.5 and GPT-4 have advanced the performance of AI systems on various natural language processing tasks to human-like levels. However their generalisation and robustness when performing logical reasoning has not been sufficiently assessed. To comprehensively evaluate this ability we develop three new logical reasoning datasets named ReClor-plus LogiQA-plus and LogiQAv2-plus that extend standard logical reasoning datasets to evaluate the robustness of the LLMs reasoning. For each we create three subsets the first with randomly shuffled options the second with the correct choices replaced by none of the other options is correct and the third with a combination of shuffling and substitution. Experiments on these datasets show that these simple augmentations greatly hinder the models performance. Despite their high performance on the original publicly available datasets we find that all models perform poorly on these newly constructed datasets. We also demonstrate that introducing task variations into the training set can markedly improve the models performance on both the original and our developed datasets. Finally we show that applying logic-driven data augmentation for fine-tuning and prompting can enhance generalisation in both discriminative and generative models offering a path to improving their robustness for tasks involving logical reasoning. Source code and data are made publicly available at https://github.com/Strong-AI-Lab/Logical-and-abstract-reasoning.
