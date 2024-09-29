---
layout: publication
title: FIPO Free45;form Instruction45;oriented Prompt Optimization With Preference Dataset And Modular Fine45;tuning Schema
authors: Lu Junru, An Siyu, Zhang Min, He Yulan, Yin Di, Sun Xing
conference: "Arxiv"
year: 2024
bibkey: lu2024free
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11811"}
  - {name: "Code", url: "https://github.com/LuJunru/FIPO&#95;Project"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
When the quality of naive prompts is carefully optimized by human experts the task performance of large language models (LLMs) can be significantly improved. However expert45;based prompt optimizations are expensive. Herein some works have proposed Automatic Prompt Optimization (APO) to optimize naive prompts according to task outputs of given in45;box testing models with the help of advanced LLMs (e.g. GPT45;4) in an ad45;hoc way. Although effective existing schemes suffer from poor generalization ability and privacy risk. To this end we collect the first large45;scale Prompt Optimization Preference dataset (POP) fine45;tune offline local LLM45;based optimizers then fairly test with various downstream models. Our method allows accurate optimization of the core task instruction part within the naive prompt in a model45;agnostic manner and thus is named Free45;from Instruction45;oriented Prompt Optimization (FIPO). In specific FIPO uses a modular APO template that dynamically integrate the naive task instruction optional instruction responses and optional ground truth to produce finely optimized prompts. The POP dataset is meticulously constructed using advanced LLMs undergoing rigorous cross45;validation by human experts and analytical models. Leveraging insights from the data with Tulu2 models and diverse fine45;tuning strategies we validate the efficacy of FIPO framework across five public benchmarks and six testing models. Check codes and data here https://github.com/LuJunru/FIPO&#95;Project.
