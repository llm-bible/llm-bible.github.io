---
layout: publication
title: Larger Language Models Dont Care How You Think Why Chain45;of45;thought Prompting Fails In Subjective Tasks
authors: Chochlakis Georgios, Pandiyan Niyantha Maruthu, Lerman Kristina, Narayanan Shrikanth
conference: "Arxiv"
year: 2024
bibkey: chochlakis2024larger
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06173"}
  - {name: "Code", url: "https://github.com/gchochla/cot&#45;priors"}
tags: ['Has Code', 'Prompting']
---
In45;Context Learning (ICL) in Large Language Models (LLM) has emerged as the dominant technique for performing natural language tasks as it does not require updating the model parameters with gradient45;based methods. ICL promises to adapt the LLM to perform the present task at a competitive or state45;of45;the45;art level at a fraction of the computational cost. ICL can be augmented by incorporating the reasoning process to arrive at the final label explicitly in the prompt a technique called Chain45;of45;Thought (CoT) prompting. However recent work has found that ICL relies mostly on the retrieval of task priors and less so on learning to perform tasks especially for complex subjective domains like emotion and morality where priors ossify posterior predictions. In this work we examine whether enabling reasoning also creates the same behavior in LLMs wherein the format of CoT retrieves reasoning priors that remain relatively unchanged despite the evidence in the prompt. We find that surprisingly CoT indeed suffers from the same posterior collapse as ICL for larger language models. Code is avalaible at https://github.com/gchochla/cot&#45;priors.
