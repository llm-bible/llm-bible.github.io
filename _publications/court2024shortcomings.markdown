---
layout: publication
title: 'Shortcomings Of Llms For Low-resource Translation: Retrieval And Understanding Are Both The Problem'
authors: Sara Court, Micha Elsner
conference: "Arxiv"
year: 2024
bibkey: court2024shortcomings
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15625"}
tags: ['Prompting', 'In-Context Learning', 'Reinforcement Learning']
---
This work investigates the in-context learning abilities of pretrained large
language models (LLMs) when instructed to translate text from a low-resource
language into a high-resource language as part of an automated machine
translation pipeline. We conduct a set of experiments translating Southern
Quechua to Spanish and examine the informativity of various types of context
retrieved from a constrained database of digitized pedagogical materials
(dictionaries and grammar lessons) and parallel corpora. Using both automatic
and human evaluation of model output, we conduct ablation studies that
manipulate (1) context type (morpheme translations, grammar descriptions, and
corpus examples), (2) retrieval methods (automated vs. manual), and (3) model
type. Our results suggest that even relatively small LLMs are capable of
utilizing prompt context for zero-shot low-resource translation when provided a
minimally sufficient amount of relevant linguistic information. However, the
variable effects of context type, retrieval method, model type, and
language-specific factors highlight the limitations of using even the best LLMs
as translation systems for the majority of the world's 7,000+ languages and
their speakers.
