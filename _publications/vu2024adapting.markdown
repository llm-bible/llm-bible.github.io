---
layout: publication
title: 'Psychadapter: Adapting LLM Transformers To Reflect Traits, Personality And Mental Health'
authors: Huy Vu, Huy Anh Nguyen, Adithya V Ganesan, Swanie Juhng, Oscar N. E. Kjell, Joao Sedoc, Margaret L. Kern, Ryan L. Boyd, Lyle Ungar, H. Andrew Schwartz, Johannes C. Eichstaedt
conference: "Arxiv"
year: 2024
bibkey: vu2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16882"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Artificial intelligence-based language generators are now a part of most
people's lives. However, by default, they tend to generate "average" language
without reflecting the ways in which people differ. Here, we propose a
lightweight modification to the standard language model transformer
architecture - "PsychAdapter" - that uses empirically derived trait-language
patterns to generate natural language for specified personality, demographic,
and mental health characteristics (with or without prompting). We applied
PsychAdapters to modify OpenAI's GPT-2, Google's Gemma, and Meta's Llama 3 and
found generated text to reflect the desired traits. For example, expert raters
evaluated PsychAdapter's generated text output and found it matched intended
trait levels with 87.3% average accuracy for Big Five personalities, and 96.7%
for depression and life satisfaction. PsychAdapter is a novel method to
introduce psychological behavior patterns into language models at the
foundation level, independent of prompting, by influencing every transformer
layer. This approach can create chatbots with specific personality profiles,
clinical training tools that mirror language associated with psychological
conditionals, and machine translations that match an authors reading or
education level without taking up LLM context windows. PsychAdapter also allows
for the exploration psychological constructs through natural language
expression, extending the natural language processing toolkit to study human
psychology.
