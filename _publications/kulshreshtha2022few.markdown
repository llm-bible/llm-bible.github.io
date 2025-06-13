---
layout: publication
title: 'Few-shot Question Generation For Personalized Feedback In Intelligent Tutoring Systems'
authors: Devang Kulshreshtha, Muhammad Shayan, Robert Belfer, Siva Reddy, Iulian Vlad Serban, Ekaterina Kochmar
conference: "Arxiv"
year: 2022
bibkey: kulshreshtha2022few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.04187"}
tags: ['Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods', 'Few-Shot']
---
Existing work on generating hints in Intelligent Tutoring Systems (ITS)
focuses mostly on manual and non-personalized feedback. In this work, we
explore automatically generated questions as personalized feedback in an ITS.
Our personalized feedback can pinpoint correct and incorrect or missing phrases
in student answers as well as guide them towards correct answer by asking a
question in natural language. Our approach combines cause-effect analysis to
break down student answers using text similarity-based NLP Transformer models
to identify correct and incorrect or missing parts. We train a few-shot Neural
Question Generation and Question Re-ranking models to show questions addressing
components missing in the student answers which steers students towards the
correct answer. Our model vastly outperforms both simple and strong baselines
in terms of student learning gains by 45% and 23% respectively when tested in a
real dialogue-based ITS. Finally, we show that our personalized corrective
feedback system has the potential to improve Generative Question Answering
systems.
