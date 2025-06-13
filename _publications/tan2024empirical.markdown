---
layout: publication
title: 'An Empirical Study And Analysis Of Text-to-image Generation Using Large Language Model-powered Textual Representation'
authors: Zhiyu Tan, Mengping Yang, Luozheng Qin, Hao Yang, Ye Qian, Qiang Zhou, Cheng Zhang, Hao Li
conference: "Arxiv"
year: 2024
bibkey: tan2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12914"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
One critical prerequisite for faithful text-to-image generation is the
accurate understanding of text inputs. Existing methods leverage the text
encoder of the CLIP model to represent input prompts. However, the pre-trained
CLIP model can merely encode English with a maximum token length of 77.
Moreover, the model capacity of the text encoder from CLIP is relatively
limited compared to Large Language Models (LLMs), which offer multilingual
input, accommodate longer context, and achieve superior text representation. In
this paper, we investigate LLMs as the text encoder to improve the language
understanding in text-to-image generation. Unfortunately, training
text-to-image generative model with LLMs from scratch demands significant
computational resources and data. To this end, we introduce a three-stage
training pipeline that effectively and efficiently integrates the existing
text-to-image model with LLMs. Specifically, we propose a lightweight adapter
that enables fast training of the text-to-image model using the textual
representations from LLMs. Extensive experiments demonstrate that our model
supports not only multilingual but also longer input context with superior
image generation quality.
