---
layout: publication
title: Just Ask Learning To Answer Questions From Millions Of Narrated Videos
authors: Yang Antoine, Miech Antoine, Sivic Josef, Laptev Ivan, Schmid Cordelia
conference: "Arxiv"
year: 2020
bibkey: yang2020just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.00451"}
  - {name: "Code", url: "https://antoyang.github.io/just&#45;ask.html"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Recent methods for visual question answering rely on large45;scale annotated datasets. Manual annotation of questions and answers for videos however is tedious expensive and prevents scalability. In this work we propose to avoid manual annotation and generate a large45;scale training dataset for video question answering making use of automatic cross45;modal supervision. We leverage a question generation transformer trained on text data and use it to generate question45;answer pairs from transcribed video narrations. Given narrated videos we then automatically generate the HowToVQA69M dataset with 69M video45;question45;answer triplets. To handle the open vocabulary of diverse answers in this dataset we propose a training procedure based on a contrastive loss between a video45;question multi45;modal transformer and an answer transformer. We introduce the zero45;shot VideoQA task and show excellent results in particular for rare answers. Furthermore we demonstrate our method to significantly outperform the state of the art on MSRVTT45;QA MSVD45;QA ActivityNet45;QA and How2QA. Finally for a detailed evaluation we introduce iVQA a new VideoQA dataset with reduced language biases and high45;quality redundant manual annotations. Our code datasets and trained models are available at https://antoyang.github.io/just&#45;ask.html.
