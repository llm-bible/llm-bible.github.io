---
layout: publication
title: 'Distilling Reasoning Ability From Large Language Models With Adaptive Thinking'
authors: Chen Xiaoshu, Zhou Sihang, Liang Ke, Liu Xinwang
conference: "Arxiv"
year: 2024
bibkey: chen2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09170"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Prompting']
---
Chain of thought finetuning (cot-finetuning) aims to endow small language models (SLM) with reasoning ability to improve their performance towards specific tasks by allowing them to imitate the reasoning procedure of large language models (LLM) beyond simply predicting the answers. Most existing cot-finetuning methods adopt a pre-thinking mechanism allowing the SLM to generate a rationale before providing an answer. This mechanism enables SLM to analyze and think about complex questions but it also makes answer correctness highly sensitive to minor errors in rationale. Therefore we propose a robust post-thinking mechanism to generate answers before rationale. Thanks to this answer-first setting 1) the answer can escape from the adverse effects caused by minor errors in the rationale; 2) the rationale serves as an error amplifier to the answer which makes the SLM focus on learning hard samples; 3) the inferring efficiency can also benefit from the setting since users can stop the generation right after answers are outputted when inference is conducted. However although the post-thinking mechanism brings many advantages and improves the overall performance of SLM on specific tasks it may lose the ability to think about the questions and decompose complex questions into simple sub-questions compared to pre-thinking mechanism. Therefore a plug-and-play adaptive-thinking mechanism is proposed with the aid of the soft prompt tuning to integrate the merits of the pre-thinking mechanism and post-thinking mechanism in which a perception module is introduced to adaptively prompt SLM answer or think first based on perceiving the complexity of the questions. Extensive experiments are conducted across 12 reasoning tasks and 2 representative language models to demonstrate the effectiveness of the proposed mechanism.
