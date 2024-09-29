---
layout: publication
title: An Empirical Study And Analysis Of Text45;to45;image Generation Using Large Language Model45;powered Textual Representation
authors: Tan Zhiyu, Yang Mengping, Qin Luozheng, Yang Hao, Qian Ye, Zhou Qiang, Zhang Cheng, Li Hao
conference: "Arxiv"
year: 2024
bibkey: tan2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12914"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
One critical prerequisite for faithful text45;to45;image generation is the accurate understanding of text inputs. Existing methods leverage the text encoder of the CLIP model to represent input prompts. However the pre45;trained CLIP model can merely encode English with a maximum token length of 77. Moreover the model capacity of the text encoder from CLIP is relatively limited compared to Large Language Models (LLMs) which offer multilingual input accommodate longer context and achieve superior text representation. In this paper we investigate LLMs as the text encoder to improve the language understanding in text45;to45;image generation. Unfortunately training text45;to45;image generative model with LLMs from scratch demands significant computational resources and data. To this end we introduce a three45;stage training pipeline that effectively and efficiently integrates the existing text45;to45;image model with LLMs. Specifically we propose a lightweight adapter that enables fast training of the text45;to45;image model using the textual representations from LLMs. Extensive experiments demonstrate that our model supports not only multilingual but also longer input context with superior image generation quality.
