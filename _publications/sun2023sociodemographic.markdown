---
layout: publication
title: 'Sociodemographic Prompting Is Not Yet An Effective Approach For Simulating Subjective Judgments With Llms'
authors: Huaman Sun, Jiaxin Pei, Minje Choi, David Jurgens
conference: "Arxiv"
year: 2023
bibkey: sun2023sociodemographic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09730"}
  - {name: "Code", url: "https://github.com/Jiaxin-Pei/LLM-as-Subjective-Judge"}
tags: ['RAG', 'Has Code', 'Prompting', 'Ethics and Bias']
---
Human judgments are inherently subjective and are actively affected by
personal traits such as gender and ethnicity. While Large Language Models
(LLMs) are widely used to simulate human responses across diverse contexts,
their ability to account for demographic differences in subjective tasks
remains uncertain. In this study, leveraging the POPQUORN dataset, we evaluate
nine popular LLMs on their ability to understand demographic differences in two
subjective judgment tasks: politeness and offensiveness. We find that in
zero-shot settings, most models' predictions for both tasks align more closely
with labels from White participants than those from Asian or Black
participants, while only a minor gender bias favoring women appears in the
politeness task. Furthermore, sociodemographic prompting does not consistently
improve and, in some cases, worsens LLMs' ability to perceive language from
specific sub-populations. These findings highlight potential demographic biases
in LLMs when performing subjective judgment tasks and underscore the
limitations of sociodemographic prompting as a strategy to achieve pluralistic
alignment. Code and data are available at:
https://github.com/Jiaxin-Pei/LLM-as-Subjective-Judge.
