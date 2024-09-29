---
layout: publication
title: Multi45;frame Lightweight amp; Efficient Vision45;language Models For Question Answering In Autonomous Driving
authors: Gopalkrishnan Akshay, Greer Ross, Trivedi Mohan
conference: "Arxiv"
year: 2024
bibkey: gopalkrishnan2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19838"}
  - {name: "Code", url: "https://github.com/akshaygopalkr/EM&#45;VLM4AD"}
tags: ['Applications', 'Has Code', 'Masked Language Model', 'Prompting', 'Responsible AI']
---
Vision45;Language Models (VLMs) and Multi45;Modal Language models (MMLMs) have become prominent in autonomous driving research as these models can provide interpretable textual reasoning and responses for end45;to45;end autonomous driving safety tasks using traffic scene images and other data modalities. However current approaches to these systems use expensive large language model (LLM) backbones and image encoders making such systems unsuitable for real45;time autonomous driving systems where tight memory constraints exist and fast inference time is necessary. To address these previous issues we develop EM45;VLM4AD an efficient lightweight multi45;frame vision language model which performs Visual Question Answering for autonomous driving. In comparison to previous approaches EM45;VLM4AD requires at least 10 times less memory and floating point operations while also achieving higher CIDEr and ROUGE45;L scores than the existing baseline on the DriveLM dataset. EM45;VLM4AD also exhibits the ability to extract relevant information from traffic views related to prompts and can answer questions for various autonomous driving subtasks. We release our code to train and evaluate our model at https://github.com/akshaygopalkr/EM&#45;VLM4AD.
