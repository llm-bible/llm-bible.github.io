---
layout: publication
title: Can Separators Improve Chain-of-Thought Prompting
authors: Park Yoonjeong, Kim Hyunjin, Choi Chanyeol, Kim Junseong, Sohn Jy-yong
conference: "Arxiv"
year: 2024
bibkey: park2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10645"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Chain-of-thought (CoT) prompting is a simple and effective method for improving the reasoning capabilities of Large Language Models (LLMs). The basic idea of CoT is to let LLMs break down their thought processes step-by-step by putting exemplars in the input prompt. However the densely structured prompt exemplars of CoT may cause the cognitive overload of LLMs. Inspired by human cognition we introduce COT-SEP a method that strategically employs separators at the end of each exemplar in CoT prompting. These separators are designed to help the LLMs understand their thought processes better while reasoning. Interestingly it turns out that COT-SEP significantly improves the LLMs performances on complex reasoning tasks (e.g. GSM8K AQuA CSQA) compared with the vanilla CoT which does not use separators. We also study the effects of the type and the location of separators tested on multiple LLMs including GPT-3.5-Turbo GPT-4 and LLaMA-2 7B.
