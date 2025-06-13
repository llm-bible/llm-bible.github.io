---
layout: publication
title: 'When "A Helpful Assistant" Is Not Really Helpful: Personas In System Prompts Do Not Improve Performances Of Large Language Models'
authors: Mingqian Zheng, Jiaxin Pei, Lajanugen Logeswaran, Moontae Lee, David Jurgens
conference: "Arxiv"
year: 2023
bibkey: zheng2023when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10054"}
  - {name: "Code", url: "https://github.com/Jiaxin-Pei/Prompting-with-Social-Roles"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Has Code']
---
Prompting serves as the major way humans interact with Large Language Models
(LLM). Commercial AI systems commonly define the role of the LLM in system
prompts. For example, ChatGPT uses ``You are a helpful assistant'' as part of
its default system prompt. Despite current practices of adding personas to
system prompts, it remains unclear how different personas affect a model's
performance on objective tasks. In this study, we present a systematic
evaluation of personas in system prompts. We curate a list of 162 roles
covering 6 types of interpersonal relationships and 8 domains of expertise.
Through extensive analysis of 4 popular families of LLMs and 2,410 factual
questions, we demonstrate that adding personas in system prompts does not
improve model performance across a range of questions compared to the control
setting where no persona is added. Nevertheless, further analysis suggests that
the gender, type, and domain of the persona can all influence the resulting
prediction accuracies. We further experimented with a list of persona search
strategies and found that, while aggregating results from the best persona for
each question significantly improves prediction accuracy, automatically
identifying the best persona is challenging, with predictions often performing
no better than random selection. Overall, our findings suggest that while
adding a persona may lead to performance gains in certain settings, the effect
of each persona can be largely random. Code and data are available at
https://github.com/Jiaxin-Pei/Prompting-with-Social-Roles.
