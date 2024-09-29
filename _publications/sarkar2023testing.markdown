---
layout: publication
title: Testing the Limits of Unified Sequence to Sequence LLM Pretraining on Diverse Table Data Tasks
authors: Sarkar Soumajyoti, Lausen Leonard
conference: "Arxiv"
year: 2023
bibkey: sarkar2023testing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00789"}
tags: ['Applications', 'Pretraining Methods', 'Training Techniques']
---
Tables stored in databases and tables which are present in web pages and articles account for a large part of semi-structured data that is available on the internet. It then becomes pertinent to develop a modeling approach with large language models (LLMs) that can be used to solve diverse table tasks such as semantic parsing question answering as well as classification problems. Traditionally there existed separate models specialized for each task individually. It raises the question of how far can we go to build a unified model that works well on some table tasks without significant degradation on others. To that end we attempt at creating a shared modeling approach in the pretraining stage with encoder-decoder style LLMs that can cater to diverse tasks. We evaluate our approach that continually pretrains and finetunes different model families of T5 with data from tables and surrounding context on these downstream tasks at different model scales. Through multiple ablation studies we observe that our pretraining with self-supervised objectives can significantly boost the performance of the models on these tasks. As an example of one improvement we observe that the instruction finetuned public models which come specialized on text question answering (QA) and have been trained on table data still have room for improvement when it comes to table specific QA. Our work is the first attempt at studying the advantages of a unified approach to table specific pretraining when scaled from 770M to 11B sequence to sequence models while also comparing the instruction finetuned variants of the models.
