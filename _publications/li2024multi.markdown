---
layout: publication
title: Multi-modal preference alignment remedies regression of visual instruction tuning on language model
authors: Li Shengzhi, Lin Rongyu, Pei Shichao
conference: "Arxiv"
year: 2024
bibkey: li2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10884"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
In production multi-modal large language models (MLLMs) are expected to support multi-turn queries of interchanging image and text modalities. However the current MLLMs trained with visual-question-answering (VQA) datasets could suffer from degradation as VQA datasets lack the diversity and complexity of the original text instruction datasets which the underlying language model had been trained with. To address this challenging degradation we first collect a lightweight (6k entries) VQA preference dataset where answers were annotated by Gemini for 5 quality metrics in a granular fashion and investigate standard Supervised Fine-tuning rejection sampling Direct Preference Optimization (DPO) and SteerLM. Our findings indicate that the with DPO we are able to surpass instruction-following capabilities of the language model achieving a 6.73 score on MT-Bench compared to Vicunas 6.57 and LLaVAs 5.99 despite small data scale. This enhancement in textual instruction proficiency correlates with boosted visual instruction performance (+4.9 on MM-Vet +6 on LLaVA-Bench) with minimal alignment tax on visual knowledge benchmarks compared to previous RLHF approach. In conclusion we propose a distillation-based multi-modal alignment model with fine-grained annotations on a small dataset that reconciles the textual and visual performance of MLLMs restoring and boosting language capability after visual instruction tuning.
