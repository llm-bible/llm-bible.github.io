---
layout: publication
title: 'Track The Answer: Extending Textvqa From Image To Video With Spatio-temporal Clues'
authors: Yan Zhang, Gangyan Zeng, Huawen Shen, Daiqing Wu, Yu Zhou, Can Ma
conference: "Arxiv"
year: 2024
bibkey: zhang2024track
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12502"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Applications']
---
Video text-based visual question answering (Video TextVQA) is a practical
task that aims to answer questions by jointly reasoning textual and visual
information in a given video. Inspired by the development of TextVQA in image
domain, existing Video TextVQA approaches leverage a language model (e.g. T5)
to process text-rich multiple frames and generate answers auto-regressively.
Nevertheless, the spatio-temporal relationships among visual entities
(including scene text and objects) will be disrupted and models are susceptible
to interference from unrelated information, resulting in irrational reasoning
and inaccurate answering. To tackle these challenges, we propose the TEA
(stands for ``\textbf\{T\}rack th\textbf\{E\} \textbf\{A\}nswer'') method that better
extends the generative TextVQA framework from image to video. TEA recovers the
spatio-temporal relationships in a complementary way and incorporates OCR-aware
clues to enhance the quality of reasoning questions. Extensive experiments on
several public Video TextVQA datasets validate the effectiveness and
generalization of our framework. TEA outperforms existing TextVQA methods,
video-language pretraining methods and video large language models by great
margins.
