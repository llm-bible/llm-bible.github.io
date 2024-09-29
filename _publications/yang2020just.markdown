---
layout: publication
title: Just Ask Learning to Answer Questions from Millions of Narrated Videos
authors: Yang Antoine, Miech Antoine, Sivic Josef, Laptev Ivan, Schmid Cordelia
conference: "Arxiv"
year: 2020
bibkey: yang2020just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.00451"}
  - {name: "Code", url: "https://antoyang.github.io/just-ask.html"}
tags: ['Applications', 'Ethics And Bias', 'Has Code', 'Large Scale Training', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Recent methods for visual question answering rely on large-scale annotated datasets. Manual annotation of questions and answers for videos however is tedious expensive and prevents scalability. In this work we propose to avoid manual annotation and generate a large-scale training dataset for video question answering making use of automatic cross-modal supervision. We leverage a question generation transformer trained on text data and use it to generate question-answer pairs from transcribed video narrations. Given narrated videos we then automatically generate the HowToVQA69M dataset with 69M video-question-answer triplets. To handle the open vocabulary of diverse answers in this dataset we propose a training procedure based on a contrastive loss between a video-question multi-modal transformer and an answer transformer. We introduce the zero-shot VideoQA task and show excellent results in particular for rare answers. Furthermore we demonstrate our method to significantly outperform the state of the art on MSRVTT-QA MSVD-QA ActivityNet-QA and How2QA. Finally for a detailed evaluation we introduce iVQA a new VideoQA dataset with reduced language biases and high-quality redundant manual annotations. Our code datasets and trained models are available at https://antoyang.github.io/just-ask.html.
