---
layout: publication
title: What Does BERT Know About Books Movies And Music Probing BERT For Conversational Recommendation
authors: Penha Gustavo, Hauff Claudia
conference: "Arxiv"
year: 2020
bibkey: penha2020what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.15356"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques', 'Transformer']
---
Heavily pre45;trained transformer models such as BERT have recently shown to be remarkably powerful at language modelling by achieving impressive results on numerous downstream tasks. It has also been shown that they are able to implicitly store factual knowledge in their parameters after pre45;training. Understanding what the pre45;training procedure of LMs actually learns is a crucial step for using and improving them for Conversational Recommender Systems (CRS). We first study how much off45;the45;shelf pre45;trained BERT knows about recommendation items such as books movies and music. In order to analyze the knowledge stored in BERTs parameters we use different probes that require different types of knowledge to solve namely content45;based and collaborative45;based. Content45;based knowledge is knowledge that requires the model to match the titles of items with their content information such as textual descriptions and genres. In contrast collaborative45;based knowledge requires the model to match items with similar ones according to community interactions such as ratings. We resort to BERTs Masked Language Modelling head to probe its knowledge about the genre of items with cloze style prompts. In addition we employ BERTs Next Sentence Prediction head and representations similarity to compare relevant and non45;relevant search and recommendation query45;document inputs to explore whether BERT can without any fine45;tuning rank relevant items first. Finally we study how BERT performs in a conversational recommendation downstream task. Overall our analyses and experiments show that (i) BERT has knowledge stored in its parameters about the content of books movies and music; (ii) it has more content45;based knowledge than collaborative45;based knowledge; and (iii) fails on conversational recommendation when faced with adversarial data.
