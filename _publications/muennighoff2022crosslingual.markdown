---
layout: publication
title: Crosslingual Generalization Through Multitask Finetuning
authors: Niklas Muennighoff, Thomas Wang, Lintang Sutawika, Adam Roberts, Stella Biderman, Teven Le Scao, M Saiful Bari, Sheng Shen, Zheng-xin Yong, Hailey Schoelkopf, Xiangru Tang, Dragomir Radev, Alham Fikri Aji, Khalid Almubarak, Samuel Albanie, Zaid Alyafeai, Albert Webson, Edward Raff, Colin Raffel
conference: "Arxiv"
year: 2022
bibkey: muennighoff2022crosslingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2211.01786v2"}
  - {name: "Code", url: "https://github.com/bigscience&#45;workshop/xmtf"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Multitask prompted finetuning (MTF) has been shown to help large language models generalize to new tasks in a zero45;shot setting but so far explorations of MTF have focused on English data and models. We apply MTF to the pretrained multilingual BLOOM and mT5 model families to produce finetuned variants called BLOOMZ and mT0. We find finetuning large multilingual language models on English tasks with English prompts allows for task generalization to non45;English languages that appear only in the pretraining corpus. Finetuning on multilingual tasks with English prompts further improves performance on English and non45;English tasks leading to various state45;of45;the45;art zero45;shot results. We also investigate finetuning on multilingual tasks with prompts that have been machine45;translated from English to match the language of each dataset. We find training on these machine45;translated prompts leads to better performance on human45;written prompts in the respective languages. Surprisingly we find models are capable of zero45;shot generalization to tasks in languages they have never intentionally seen. We conjecture that the models are learning higher45;level capabilities that are both task45; and language45;agnostic. In addition we introduce xP3 a composite of supervised datasets in 46 languages with English and machine45;translated prompts. Our code datasets and models are freely available at https://github.com/bigscience&#45;workshop/xmtf.
