---
layout: publication
title: Unfamiliar Finetuning Examples Control How Language Models Hallucinate
authors: Kang Katie, Wallace Eric, Tomlin Claire, Kumar Aviral, Levine Sergey
conference: "Arxiv"
year: 2024
bibkey: kang2024unfamiliar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05612"}
tags: ['Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large language models are known to hallucinate when faced with unfamiliar queries but the underlying mechanism that govern how models hallucinate are not yet fully understood. In this work we find that unfamiliar examples in the models finetuning data 45;45; those that introduce concepts beyond the base models scope of knowledge 45;45; are crucial in shaping these errors. In particular we find that an LLMs hallucinated predictions tend to mirror the responses associated with its unfamiliar finetuning examples. This suggests that by modifying how unfamiliar finetuning examples are supervised we can influence a models responses to unfamiliar queries (e.g. say I dont know). We empirically validate this observation in a series of controlled experiments involving SFT RL and reward model finetuning on TriviaQA and MMLU. Our work further investigates RL finetuning strategies for improving the factuality of long45;form model generations. We find that while hallucinations from the reward model can significantly undermine the effectiveness of RL factuality finetuning strategically controlling how reward models hallucinate can minimize these negative effects. Leveraging our previous observations on controlling hallucinations we propose an approach for learning more reliable reward models and show that they improve the efficacy of RL factuality finetuning in long45;form biography and book/movie plot generation tasks.
