---
layout: publication
title: 'Uncovering Autoregressive LLM Knowledge Of Thematic Fit In Event Representation'
authors: Safeyah Khaled Alshemali, Daniel Bauer, Yuval Marton
conference: "Arxiv"
year: 2024
bibkey: alshemali2024uncovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15173"}
tags: ['Prompting', 'Pretraining Methods', 'Model Architecture', 'GPT']
---
The thematic fit estimation task measures the compatibility between a
predicate (typically a verb), an argument (typically a noun phrase), and a
specific semantic role assigned to the argument. Previous state-of-the-art work
has focused on modeling thematic fit through distributional or neural models of
event representation, trained in a supervised fashion with indirect labels. In
this work, we assess whether pre-trained autoregressive LLMs possess
consistent, expressible knowledge about thematic fit. We evaluate both closed
and open state-of-the-art LLMs on several psycholinguistic datasets, along
three axes: (1) Reasoning Form: multi-step logical reasoning (chain-of-thought
prompting) vs. simple prompting. (2) Input Form: providing context (generated
sentences) vs. raw tuples <predicate, argument, role>. (3) Output Form:
categorical vs. numeric. Our results show that chain-of-thought reasoning is
more effective on datasets with self-explanatory semantic role labels,
especially Location. Generated sentences helped only in few settings, and
lowered results in many others. Predefined categorical (compared to numeric)
output raised GPT's results across the board with few exceptions, but lowered
Llama's. We saw that semantically incoherent generated sentences, which the
models lack the ability to consistently filter out, hurt reasoning and overall
performance too. Our GPT-powered methods set new state-of-the-art on all tested
datasets.
