---
layout: publication
title: 'Augmenting In-context-learning In Llms Via Automatic Data Labeling And Refinement'
authors: Joseph Shtok, Amit Alfassy, Foad Abo Dahood, Eliyahu Schwartz, Sivan Doveh, Assaf Arbelle
conference: "Arxiv"
year: 2024
bibkey: shtok2024augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10348"}
tags: ['Agentic', 'Prompting', 'In-Context Learning']
---
It has been shown that Large Language Models' (LLMs) performance can be
improved for many tasks using Chain of Thought (CoT) or In-Context Learning
(ICL), which involve demonstrating the steps needed to solve a task using a few
examples. However, while datasets with input-output pairs are relatively easy
to produce, providing demonstrations which include intermediate steps requires
cumbersome manual work. These steps may be executable programs, as in agentic
flows, or step-by-step reasoning as in CoT. In this work, we propose Automatic
Data Labeling and Refinement (ADLR), a method to automatically generate and
filter demonstrations which include the above intermediate steps, starting from
a small seed of manually crafted examples. We demonstrate the advantage of ADLR
in code-based table QA and mathematical reasoning, achieving up to a 5.5% gain.
The code implementing our method is provided in the Supplementary material and
will be made available.
