---
layout: publication
title: 'Analyzing The Effectiveness Of Large Language Models On Text-to-sql Synthesis'
authors: Richard Roberson, Gowtham Kaki, Ashutosh Trivedi
conference: "Arxiv"
year: 2024
bibkey: roberson2024analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12379"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
This study investigates various approaches to using Large Language Models
(LLMs) for Text-to-SQL program synthesis, focusing on the outcomes and insights
derived. Employing the popular Text-to-SQL dataset, spider, the goal was to
input a natural language question along with the database schema and output the
correct SQL SELECT query. The initial approach was to fine-tune a local and
open-source model to generate the SELECT query. After QLoRa fine-tuning
WizardLM's WizardCoder-15B model on the spider dataset, the execution accuracy
for generated queries rose to a high of 61%. With the second approach, using
the fine-tuned gpt-3.5-turbo-16k (Few-shot) + gpt-4-turbo (Zero-shot error
correction), the execution accuracy reached a high of 82.1%. Of all the
incorrect queries, most can be categorized into a seven different categories of
what went wrong: selecting the wrong columns or wrong order of columns,
grouping by the wrong column, predicting the wrong values in conditionals,
using different aggregates than the ground truth, extra or too few JOIN
clauses, inconsistencies in the Spider dataset, and lastly completely incorrect
query structure. Most if not all of the queries fall into these categories and
it is insightful to understanding where the faults still lie with LLM program
synthesis and where they can be improved.
