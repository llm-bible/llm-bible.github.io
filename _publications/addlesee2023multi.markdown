---
layout: publication
title: 'Multi-party Goal Tracking With Llms: Comparing Pre-training, Fine-tuning, And Prompt Engineering'
authors: Angus Addlesee, Weronika Sieińska, Nancie Gunson, Daniel Hernández Garcia, Christian Dondrup, Oliver Lemon
conference: "Arxiv"
year: 2023
bibkey: addlesee2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15231"}
tags: ['Fine-Tuning', 'Responsible AI', 'Pre-Training', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
This paper evaluates the extent to which current Large Language Models (LLMs)
can capture task-oriented multi-party conversations (MPCs). We have recorded
and transcribed 29 MPCs between patients, their companions, and a social robot
in a hospital. We then annotated this corpus for multi-party goal-tracking and
intent-slot recognition. People share goals, answer each other's goals, and
provide other people's goals in MPCs - none of which occur in dyadic
interactions. To understand user goals in MPCs, we compared three methods in
zero-shot and few-shot settings: we fine-tuned T5, created pre-training tasks
to train DialogLM using LED, and employed prompt engineering techniques with
GPT-3.5-turbo, to determine which approach can complete this novel task with
limited data. GPT-3.5-turbo significantly outperformed the others in a few-shot
setting. The `reasoning' style prompt, when given 7% of the corpus as example
annotated conversations, was the best performing method. It correctly annotated
62.32% of the goal tracking MPCs, and 69.57% of the intent-slot recognition
MPCs. A `story' style prompt increased model hallucination, which could be
detrimental if deployed in safety-critical settings. We conclude that
multi-party conversations still challenge state-of-the-art LLMs.
