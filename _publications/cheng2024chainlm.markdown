---
layout: publication
title: ChainLM Empowering Large Language Models with Improved Chain-of-Thought Prompting
authors: Cheng Xiaoxue, Li Junyi, Zhao Wayne Xin, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: cheng2024chainlm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14312"}
  - {name: "Code", url: "https://github.com/RUCAIBox/ChainLM"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Tools']
---
Chain-of-Thought (CoT) prompting can enhance the reasoning capabilities of large language models (LLMs) establishing itself as a primary approach to solving complex reasoning tasks. Existing CoT synthesis approaches usually focus on simpler reasoning tasks and thus result in low-quality and inconsistent CoT prompts. In response to this challenge we present an empirical investigation of CoT prompting and introduce CoTGenius a novel framework designed for the automatic generation of superior CoT prompts. CoTGenius is developed based on three major evolution strategies i.e. complicate diversify and specify-alongside two filtering mechanisms evolutionary success judgement and correctness verification. We further employ CoTGenius to create an extensive CoT dataset and subsequently fine-tune the Llama 2-Chat 7B and 13B models on this dataset. We call the resulting model ChainLM. To deal with the cumulative error issue in reasoning steps we propose a step-level debating method wherein multiple debaters discuss each reasoning step to arrive at the correct answer. Extensive experiments demonstrate that our ChainLM models exhibit enhanced proficiency in addressing a spectrum of complex reasoning problems compared to existing models. In addition we conduct an in-depth analysis of the impact of data categories within CoTGenius on the model performance. We release our dataset and code at https://github.com/RUCAIBox/ChainLM.
