---
layout: publication
title: 'Reducing Selection Bias In Large Language Models'
authors: Eicher J. E., Irgolič R. F.
conference: "Arxiv"
year: 2024
bibkey: eicher2024reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01740"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) like gpt-3.5-turbo-0613 and claude-instant-1.2 are vital in interpreting and executing semantic tasks. Unfortunately these models inherent biases adversely affect their performance Particularly affected is object selection from lists; a fundamental operation in digital navigation and decision-making. This research critically examines these biases and quantifies the effects on a representative list selection task. To explore these biases we experiment manipulating temperature list length object identity object type prompt complexity and model. We isolated and measured the influence of the biases on selection behavior. Our findings show that bias structure is strongly dependent on the model with object type modulating the magnitude of the effect. With a strong primacy effect causing the first objects in a list to be disproportionately represented in outputs. The usage of guard rails a prompt engineering method of ensuring a response structure increases bias and decreases instruction adherence when to a selection task. The bias is ablated when the guard rail step is separated from the list sampling step lowering the complexity of each individual task. We provide LLM applications and theoretically suggest that LLMs experience a form of cognitive load that is compensated for with bias.
