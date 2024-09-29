---
layout: publication
title: FIPO Free-form Instruction-oriented Prompt Optimization With Preference Dataset And Modular Fine-tuning Schema
authors: Lu Junru, An Siyu, Zhang Min, He Yulan, Yin Di, Sun Xing
conference: "Arxiv"
year: 2024
bibkey: lu2024free
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11811"}
  - {name: "Code", url: "https://github.com/LuJunru/FIPO_Project"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
When the quality of naive prompts is carefully optimized by human experts the task performance of large language models (LLMs) can be significantly improved. However expert-based prompt optimizations are expensive. Herein some works have proposed Automatic Prompt Optimization (APO) to optimize naive prompts according to task outputs of given in-box testing models with the help of advanced LLMs (e.g. GPT-4) in an ad-hoc way. Although effective existing schemes suffer from poor generalization ability and privacy risk. To this end we collect the first large-scale Prompt Optimization Preference dataset (POP) fine-tune offline local LLM-based optimizers then fairly test with various downstream models. Our method allows accurate optimization of the core task instruction part within the naive prompt in a model-agnostic manner and thus is named Free-from Instruction-oriented Prompt Optimization (FIPO). In specific FIPO uses a modular APO template that dynamically integrate the naive task instruction optional instruction responses and optional ground truth to produce finely optimized prompts. The POP dataset is meticulously constructed using advanced LLMs undergoing rigorous cross-validation by human experts and analytical models. Leveraging insights from the data with Tulu2 models and diverse fine-tuning strategies we validate the efficacy of FIPO framework across five public benchmarks and six testing models. Check codes and data here https://github.com/LuJunru/FIPO\_Project.
