---
layout: publication
title: 'Japanese-english Sentence Translation Exercises Dataset For Automatic Grading'
authors: Naoki Miura, Hiroaki Funayama, Seiya Kikuchi, Yuichiroh Matsubayashi, Yuya Iwase, Kentaro Inui
conference: "Arxiv"
year: 2024
bibkey: miura2024japanese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03396"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'BERT', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
This paper proposes the task of automatic assessment of Sentence Translation
Exercises (STEs), that have been used in the early stage of L2 language
learning. We formalize the task as grading student responses for each rubric
criterion pre-specified by the educators. We then create a dataset for STE
between Japanese and English including 21 questions, along with a total of 3,
498 student responses (167 on average). The answer responses were collected
from students and crowd workers. Using this dataset, we demonstrate the
performance of baselines including finetuned BERT and GPT models with few-shot
in-context learning. Experimental results show that the baseline model with
finetuned BERT was able to classify correct responses with approximately 90% in
F1, but only less than 80% for incorrect responses. Furthermore, the GPT models
with few-shot learning show poorer results than finetuned BERT, indicating that
our newly proposed task presents a challenging issue, even for the
stateof-the-art large language models.
