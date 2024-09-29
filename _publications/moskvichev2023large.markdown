---
layout: publication
title: Narrativexl&#58; A Large-scale Dataset For Long-term Memory Models
authors: Moskvichev Arseny, Mai Ky-vinh
conference: "Arxiv"
year: 2023
bibkey: moskvichev2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13877"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
We propose a new large-scale (nearly a million questions) ultra-long-context (more than 50000 words average document length) reading comprehension dataset. Using GPT 3.5 we summarized each scene in 1500 hand-curated fiction books from Project Gutenberg which resulted in approximately 150 scene-level summaries per book. After that we created a number of reading comprehension questions based on these summaries including three types of multiple-choice scene recognition questions as well as free-form narrative reconstruction questions. With 990595 total questions our dataset is an order of magnitude larger than the closest alternatives. Crucially most questions have a known retention demand indicating how long-term of a memory is needed to answer them which should aid long-term memory performance evaluation. We validate our data in four small-scale experiments one with human labelers and three with existing language models. We show that our questions 1) adequately represent the source material 2) can be used to diagnose a models memory capacity 3) are not trivial for modern language models even when the memory demand does not exceed those models context lengths. Lastly we provide our code which can be used to further expand the dataset with minimal human labor.
