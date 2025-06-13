---
layout: publication
title: 'A Question-answer Driven Approach To Reveal Affirmative Interpretations From Verbal Negations'
authors: Md Mosharaf Hossain, Luke Holman, Anusha Kakileti, Tiffany Iris Kao, Nathan Raul Brito, Aaron Abraham Mathews, Eduardo Blanco
conference: "Arxiv"
year: 2022
bibkey: hossain2022question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.11467"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
This paper explores a question-answer driven approach to reveal affirmative
interpretations from verbal negations (i.e., when a negation cue grammatically
modifies a verb). We create a new corpus consisting of 4,472 verbal negations
and discover that 67.1% of them convey that an event actually occurred.
Annotators generate and answer 7,277 questions for the 3,001 negations that
convey an affirmative interpretation. We first cast the problem of revealing
affirmative interpretations from negations as a natural language inference
(NLI) classification task. Experimental results show that state-of-the-art
transformers trained with existing NLI corpora are insufficient to reveal
affirmative interpretations. We also observe, however, that fine-tuning brings
small improvements. In addition to NLI classification, we also explore the more
realistic task of generating affirmative interpretations directly from
negations with the T5 transformer. We conclude that the generation task remains
a challenge as T5 substantially underperforms humans.
