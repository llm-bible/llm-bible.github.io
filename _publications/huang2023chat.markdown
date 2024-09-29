---
layout: publication
title: Chat Vector A Simple Approach To Equip Llms With Instruction Following And Model Alignment In New Languages
authors: Huang Shih-cheng, Li Pin-zu, Hsu Yu-chi, Chen Kuang-ming, Lin Yu Tung, Hsiao Shih-kai, Tsai Richard Tzong-han, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: huang2023chat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04799"}
  - {name: "Code", url: "https://github.com/aqweteddy/ChatVector"}
tags: ['Has Code', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Recently the development of open45;source large language models (LLMs) has advanced rapidly. Nevertheless due to data constraints the capabilities of most open45;source LLMs are primarily focused on English. To address this issue we introduce the concept of textit123;chat vector125; to equip pre45;trained language models with instruction following and human value alignment via simple model arithmetic. The chat vector is derived by subtracting the weights of a pre45;trained base model (e.g. LLaMA2) from those of its corresponding chat model (e.g. LLaMA245;chat). By simply adding the chat vector to a continual pre45;trained models weights we can endow the model with chat capabilities in new languages without the need for further training. Our empirical studies demonstrate the superior efficacy of the chat vector from three different aspects instruction following toxicity mitigation and multi45;turn dialogue. Moreover to showcase the adaptability of our approach we extend our experiments to encompass various languages base models and chat vectors. The results underscore the chat vectors simplicity effectiveness and wide applicability making it a compelling solution for efficiently enabling conversational capabilities in pre45;trained language models. Our code is available at https://github.com/aqweteddy/ChatVector.
