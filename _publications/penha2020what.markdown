---
layout: publication
title: 'What Does BERT Know About Books, Movies And Music? Probing BERT For Conversational Recommendation'
authors: Gustavo Penha, Claudia Hauff
conference: "Arxiv"
year: 2020
bibkey: penha2020what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.15356"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Model Architecture', 'Security', 'Training Techniques', 'Masked Language Model', 'Pretraining Methods', 'BERT', 'Prompting']
---
Heavily pre-trained transformer models such as BERT have recently shown to be
remarkably powerful at language modelling by achieving impressive results on
numerous downstream tasks. It has also been shown that they are able to
implicitly store factual knowledge in their parameters after pre-training.
Understanding what the pre-training procedure of LMs actually learns is a
crucial step for using and improving them for Conversational Recommender
Systems (CRS). We first study how much off-the-shelf pre-trained BERT "knows"
about recommendation items such as books, movies and music. In order to analyze
the knowledge stored in BERT's parameters, we use different probes that require
different types of knowledge to solve, namely content-based and
collaborative-based. Content-based knowledge is knowledge that requires the
model to match the titles of items with their content information, such as
textual descriptions and genres. In contrast, collaborative-based knowledge
requires the model to match items with similar ones, according to community
interactions such as ratings. We resort to BERT's Masked Language Modelling
head to probe its knowledge about the genre of items, with cloze style prompts.
In addition, we employ BERT's Next Sentence Prediction head and
representations' similarity to compare relevant and non-relevant search and
recommendation query-document inputs to explore whether BERT can, without any
fine-tuning, rank relevant items first. Finally, we study how BERT performs in
a conversational recommendation downstream task. Overall, our analyses and
experiments show that: (i) BERT has knowledge stored in its parameters about
the content of books, movies and music; (ii) it has more content-based
knowledge than collaborative-based knowledge; and (iii) fails on conversational
recommendation when faced with adversarial data.
