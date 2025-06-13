---
layout: publication
title: 'Improving Multimodal Llms Ability In Geometry Problem Solving, Reasoning, And Multistep Scoring'
authors: Avinash Anand, Raj Jaiswal, Abhishek Dharmadhikari, Atharva Marathe, Harsh Parimal Popat, Harshil Mital, Kritarth Prasad, Rajiv Ratn Shah, Roger Zimmermann
conference: "Arxiv"
year: 2024
bibkey: anand2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00846"}
tags: ['RAG', 'Training Techniques', 'Multimodal Models']
---
This paper presents GPSM4K, a comprehensive geometry multimodal dataset
tailored to augment the problem-solving capabilities of Large Vision Language
Models (LVLMs). GPSM4K encompasses 2157 multimodal question-answer pairs
manually extracted from mathematics textbooks spanning grades 7-12 and is
further augmented to 5340 problems, consisting of both numerical and
theorem-proving questions. In contrast to PGPS9k, Geometry3K, and Geo170K which
feature only objective-type questions, GPSM4K offers detailed step-by-step
solutions in a consistent format, facilitating a comprehensive evaluation of
problem-solving approaches. This dataset serves as an excellent benchmark for
assessing the geometric reasoning capabilities of LVLMs. Evaluation of our test
set shows that there is scope for improvement needed in open-source language
models in geometry problem-solving. Finetuning on our training set increases
the geometry problem-solving capabilities of models. Further, We also evaluate
the effectiveness of techniques such as image captioning and Retrieval
Augmentation generation (RAG) on model performance. We leveraged LLM to
automate the task of final answer evaluation by providing ground truth and
predicted solutions. This research will help to assess and improve the
geometric reasoning capabilities of LVLMs.
