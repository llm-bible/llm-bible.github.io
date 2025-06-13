---
layout: publication
title: 'Canttalkaboutthis: Aligning Language Models To Stay On Topic In Dialogues'
authors: Makesh Narsimhan Sreedhar, Traian Rebedea, Shaona Ghosh, Jiaqi Zeng, Christopher Parisien
conference: "Arxiv"
year: 2024
bibkey: sreedhar2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03820"}
tags: ['Responsible AI', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Recent advancements in instruction-tuning datasets have predominantly focused
on specific tasks like mathematical or logical reasoning. There has been a
notable gap in data designed for aligning language models to maintain topic
relevance in conversations - a critical aspect for deploying chatbots to
production. We introduce the CantTalkAboutThis dataset to help language models
remain focused on the subject at hand during task-oriented interactions. It
consists of synthetic dialogues on a wide range of conversation topics from
different domains. These dialogues are interspersed with distractor turns that
intentionally divert the chatbot from the predefined topic. Fine-tuning
language models on this dataset helps make them resilient to deviating from the
role assigned and improves their ability to maintain topical coherence compared
to general-purpose instruction-tuned LLMs like GPT-4-turbo and
Mixtral-Instruct. Additionally, preliminary observations suggest that training
models on this dataset also enhance their performance on fine-grained
instruction following tasks, including safety alignment.
