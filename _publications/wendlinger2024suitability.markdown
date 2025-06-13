---
layout: publication
title: 'On The Suitability Of Pre-trained Foundational Llms For Analysis In German Legal Education'
authors: Lorenz Wendlinger, Christian Braun, Abdullah Al Zubaer, Simon Alexander Nonn, Sarah Großkopf, Christofer Fellicious, Michael Granitzer
conference: "Arxiv"
year: 2024
bibkey: wendlinger2024suitability
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15902'}
tags: ['Prompting']
---
We show that current open-source foundational LLMs possess instruction
capability and German legal background knowledge that is sufficient for some
legal analysis in an educational context. However, model capability breaks down
in very specific tasks, such as the classification of "Gutachtenstil" appraisal
style components, or with complex contexts, such as complete legal opinions.
Even with extended context and effective prompting strategies, they cannot
match the Bag-of-Words baseline. To combat this, we introduce a Retrieval
Augmented Generation based prompt example selection method that substantially
improves predictions in high data availability scenarios. We further evaluate
the performance of pre-trained LLMs on two standard tasks for argument mining
and automated essay scoring and find it to be more adequate. Throughout,
pre-trained LLMs improve upon the baseline in scenarios with little or no
labeled data with Chain-of-Thought prompting further helping in the zero-shot
case.
