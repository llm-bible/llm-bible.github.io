---
layout: publication
title: 'Building Efficient Universal Classifiers With Natural Language Inference'
authors: Laurer Moritz, Van Atteveldt Wouter, Casas Andreu, Welbers Kasper
conference: "Arxiv"
year: 2023
bibkey: laurer2023building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17543"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
'Generative Large Language Models (LLMs) have become the mainstream choice for fewshot and zeroshot learning thanks to the universality of text generation. Many users, however, do not need the broad capabilities of generative LLMs when they only want to automate a classification task. Smaller BERT-like models can also learn universal tasks, which allow them to do any text classification task without requiring fine-tuning (zeroshot classification) or to learn new tasks with only a few examples (fewshot), while being significantly more efficient than generative LLMs. This paper (1) explains how Natural Language Inference (NLI) can be used as a universal classification task that follows similar principles as instruction fine-tuning of generative LLMs, (2) provides a step-by-step guide with reusable Jupyter notebooks for building a universal classifier, and (3) shares the resulting universal classifier that is trained on 33 datasets with 389 diverse classes. Parts of the code we share has been used to train our older zeroshot classifiers that have been downloaded more than 55 million times via the Hugging Face Hub as of December 2023. Our new classifier improves zeroshot performance by 9.4&#37;.'
