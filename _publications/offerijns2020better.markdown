---
layout: publication
title: Better Distractions: Transformer-based Distractor Generation And Multiple Choice Question Filtering
authors: Offerijns Jeroen, Verberne Suzan, Verhoef Tessa
conference: "Arxiv"
year: 2020
bibkey: offerijns2020better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.09598"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
For the field of education being able to generate semantically correct and educationally relevant multiple choice questions (MCQs) could have a large impact. While question generation itself is an active research topic generating distractors (the incorrect multiple choice options) receives much less attention. A missed opportunity since there is still a lot of room for improvement in this area. In this work we train a GPT-2 language model to generate three distractors for a given question and text context using the RACE dataset. Next we train a BERT language model to answer MCQs and use this model as a filter to select only questions that can be answered and therefore presumably make sense. To evaluate our work we start by using text generation metrics which show that our model outperforms earlier work on distractor generation (DG) and achieves state-of-the-art performance. Also by calculating the question answering ability we show that larger base models lead to better performance. Moreover we conducted a human evaluation study which confirmed the quality of the generated questions but showed no statistically significant effect of the QA filter.
