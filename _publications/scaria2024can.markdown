---
layout: publication
title: "Can Small Language Models Learn, Unlearn, And Retain Noise Patterns?"
authors: Scaria Nicy, Kennedy Silvester John Joseph, Subramani Deepak
conference: "Arxiv"
year: 2024
bibkey: scaria2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00996"}
tags: ['In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Small Language Models (SLMs) are generally considered to be more compact versions of large language models (LLMs) typically having fewer than 7 billion parameters. This study investigates the ability of small language models to learn retain and subsequently eliminate noise that is typically not found on the internet where most pretraining datasets are sourced. For this four pre-trained SLMs were utilized Olmo 1B Qwen1.5 1.8B Gemma 2B and Phi2 2.7B. The models were instruction-tuned without noise and tested for task execution with in-context learning. Afterward noise patterns were introduced to evaluate the models learning and unlearning capabilities. We evaluated the models performance at various training levels. Phi consistently excelled with word-level noise but performed the worst with character-level noise. Despite being the smallest with approximately 1 billion parameters Olmo performed consistently well on tasks.
