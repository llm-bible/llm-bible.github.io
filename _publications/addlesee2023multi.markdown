---
layout: publication
title: Multi45;party Goal Tracking With Llms Comparing Pre45;training Fine45;tuning And Prompt Engineering
authors: Addlesee Angus, Sieińska Weronika, Gunson Nancie, Garcia Daniel Hernández, Dondrup Christian, Lemon Oliver
conference: "Arxiv"
year: 2023
bibkey: addlesee2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15231"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Responsible AI', 'Training Techniques']
---
This paper evaluates the extent to which current Large Language Models (LLMs) can capture task45;oriented multi45;party conversations (MPCs). We have recorded and transcribed 29 MPCs between patients their companions and a social robot in a hospital. We then annotated this corpus for multi45;party goal45;tracking and intent45;slot recognition. People share goals answer each others goals and provide other peoples goals in MPCs 45; none of which occur in dyadic interactions. To understand user goals in MPCs we compared three methods in zero45;shot and few45;shot settings we fine45;tuned T5 created pre45;training tasks to train DialogLM using LED and employed prompt engineering techniques with GPT45;3.545;turbo to determine which approach can complete this novel task with limited data. GPT45;3.545;turbo significantly outperformed the others in a few45;shot setting. The reasoning style prompt when given 737; of the corpus as example annotated conversations was the best performing method. It correctly annotated 62.3237; of the goal tracking MPCs and 69.5737; of the intent45;slot recognition MPCs. A story style prompt increased model hallucination which could be detrimental if deployed in safety45;critical settings. We conclude that multi45;party conversations still challenge state45;of45;the45;art LLMs.
