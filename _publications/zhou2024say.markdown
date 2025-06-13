---
layout: publication
title: 'Don''t Say No: Jailbreaking LLM By Suppressing Refusal'
authors: Yukai Zhou, Zhijie Huang, Feiyang Lu, Zhan Qin, Wenjie Wang
conference: "Arxiv"
year: 2024
bibkey: zhou2024say
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.16369'}
tags: ['Prompting', 'Efficiency and Optimization', 'Responsible AI', 'Security']
---
Ensuring the safety alignment of Large Language Models (LLMs) is crucial to
generating responses consistent with human values. Despite their ability to
recognize and avoid harmful queries, LLMs are vulnerable to jailbreaking
attacks, where carefully crafted prompts seduce them to produce toxic content.
One category of jailbreak attacks is reformulating the task as an optimization
by eliciting the LLM to generate affirmative responses. However, such
optimization objective has its own limitations, such as the restriction on the
predefined objectionable behaviors, leading to suboptimal attack performance.
In this study, we first uncover the reason why vanilla target loss is not
optimal, then we explore and enhance the loss objective and introduce the DSN
(Don't Say No) attack, which achieves successful attack by suppressing refusal.
Another challenge in studying jailbreak attacks is the evaluation, as it is
difficult to directly and accurately assess the harmfulness of the responses.
The existing evaluation such as refusal keyword matching reveals numerous false
positive and false negative instances. To overcome this challenge, we propose
an Ensemble Evaluation pipeline that novelly incorporates Natural Language
Inference (NLI) contradiction assessment and two external LLM evaluators.
Extensive experiments demonstrate the potential of the DSN and effectiveness of
Ensemble Evaluation compared to baseline methods.
