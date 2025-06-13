---
layout: publication
title: 'The Fellowship Of The Llms: Multi-agent Workflows For Synthetic Preference Optimization Dataset Generation'
authors: Samee Arif, Sualeha Farid, Abdul Hameed Azeemi, Awais Athar, Agha Ali Raza
conference: "Arxiv"
year: 2024
bibkey: arif2024fellowship
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.08688'}
tags: ['Agentic', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Prompting']
---
This paper presents a novel methodology for generating synthetic Preference
Optimization (PO) datasets using multi-agent workflows. We evaluate the
effectiveness and potential of these workflows in automating and enhancing the
dataset generation process. PO dataset generation requires two modules: (1)
response evaluation, and (2) response generation. In the response evaluation
module, the responses from Large Language Models (LLMs) are evaluated and
ranked - a task typically carried out by human annotators that we automate
using LLMs. We assess the response evaluation module in a 2 step process. In
step 1, we assess LLMs as evaluators using three distinct prompting strategies.
In step 2, we apply the winning prompting strategy to compare the performance
of LLM-as-a-Judge, LLMs-as-a-Jury, and LLM Debate. Our evaluation shows that
GPT-4o-as-a-Judge is more consistent across all datasets. For the response
generation module, we use the identified LLM evaluator configuration and
compare different configurations of the LLM Feedback Loop. We use the win rate
to determine the best multi-agent configuration for generation. Experimenting
with various configurations, we find that the LLM Feedback Loop, with Llama as
the generator and Gemma as the reviewer, achieves a notable 71.8% and 73.8% win
rate over single-agent Llama and Gemma, respectively. After identifying the
best configurations for both modules, we generate our PO datasets using the
above pipeline.
