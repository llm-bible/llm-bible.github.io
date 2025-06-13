---
layout: publication
title: 'Knowledgeprompts: Exploring The Abilities Of Large Language Models To Solve Proportional Analogies Via Knowledge-enhanced Prompting'
authors: Thilini Wijesiriwardene, Ruwan Wickramarachchi, Sreeram Vennam, Vinija Jain, Aman Chadha, Amitava Das, Ponnurangam Kumaraguru, Amit Sheth
conference: "Arxiv"
year: 2024
bibkey: wijesiriwardene2024exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.00869'}
  - {name: "Code", url: 'https://github.com/Thiliniiw/KnowledgePrompts/'}
tags: ['Prompting', 'Has Code', 'Applications', 'Training Techniques']
---
Making analogies is fundamental to cognition. Proportional analogies, which
consist of four terms, are often used to assess linguistic and cognitive
abilities. For instance, completing analogies like "Oxygen is to Gas as <blank>
is to <blank>" requires identifying the semantic relationship (e.g., "type of")
between the first pair of terms ("Oxygen" and "Gas") and finding a second pair
that shares the same relationship (e.g., "Aluminum" and "Metal"). In this work,
we introduce a 15K Multiple-Choice Question Answering (MCQA) dataset for
proportional analogy completion and evaluate the performance of contemporary
Large Language Models (LLMs) in various knowledge-enhanced prompt settings.
Specifically, we augment prompts with three types of knowledge: exemplar,
structured, and targeted. Our results show that despite extensive training
data, solving proportional analogies remains challenging for current LLMs, with
the best model achieving an accuracy of 55%. Notably, we find that providing
targeted knowledge can better assist models in completing proportional
analogies compared to providing exemplars or collections of structured
knowledge. Our code and data are available at:
https://github.com/Thiliniiw/KnowledgePrompts/
