---
layout: publication
title: Judging the Judges A Systematic Investigation of Position Bias in Pairwise Comparative Assessments by LLMs
authors: Shi Lin, Ma Chiyu, Ma Weicheng, Vosoughi Soroush
conference: "Arxiv"
year: 2024
bibkey: shi2024judging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07791"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'LLM', 'Prompt', 'Reinforcement Learning', 'Tools']
---
LLM-as-a-Judge offers a promising alternative to human judges across various tasks yet inherent biases particularly position bias - a systematic preference for answers based on their position in the prompt - compromise its effectiveness. Our study investigates this issue by developing a framework to systematically study and quantify position bias using metrics such as repetitional consistency positional consistency and positional fairness. We conduct experiments with 9 judge models across 22 tasks from the MTBench and DevBench benchmarks and nearly 40 answer-generating models generating approximately 80000 evaluation instances. This comprehensive assessment reveals significant variations in bias across judges and tasks. Although GPT-4 often excels in positional consistency and fairness some more cost-effective models perform comparably or even better in specific tasks highlighting essential trade-offs between consistency fairness and cost. Our results also demonstrate high consistency of judgment across repetitions confirming that position bias is not due to random variations. This research significantly contributes to the field by introducing new concepts for understanding position bias and providing a multi-dimensional framework for evaluation. These insights guide the selection of optimal judge models enhance benchmark design and lay the foundation for future research into effective debiasing strategies ultimately enhancing the reliability of LLM evaluators.
