---
layout: publication
title: 'Reprompt: Planning By Automatic Prompt Engineering For Large Language Models Agents'
authors: Weizhe Chen, Sven Koenig, Bistra Dilkina
conference: "Arxiv"
year: 2024
bibkey: chen2024planning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11132"}
tags: ['Agentic', 'Tools', 'RAG', 'Training Techniques', 'Prompting']
---
In the past year, large language models (LLMs) have had remarkable success in
domains outside the traditional natural language processing, and their capacity
is further expanded into the so-called LLM agents when connected with external
tools. In all domains, the prompt to the LLMs has been shown to make a big
difference in what the LLM would generate and thus affect the performance of
the LLM agents. Therefore, automatic prompt engineering (APE) has become an
important question for many researchers and users of LLMs. However, previous
works in APE rely on a final checker to evaluate the performance of the given
prompt -- a requirement that is hard to meet in the case of LLM agents, where
intermediate feedback is easier to obtain, and the final evaluation could be
expensive, inaccurate, or even missing. In this paper, we propose a novel
method, \textsc\{RePrompt\}, which does a ``gradient descent"-like approach to
optimize the step-by-step instructions in the prompts given to LLM agents,
based on the chat history obtained from interactions and reflections with LLM
agents. By leveraging intermediate feedback, \textsc\{RePrompt\} can optimize the
prompt without the need for a final solution checker. We evaluate our approach
on PDDL generation, TravelPlanner, and Meeting Planning to show that our method
could generally improve performance for different reasoning tasks.
