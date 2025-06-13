---
layout: publication
title: 'Learning To Answer Visual Questions From Web Videos'
authors: Antoine Yang, Antoine Miech, Josef Sivic, Ivan Laptev, Cordelia Schmid
conference: "Arxiv"
year: 2022
bibkey: yang2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.05019"}
  - {name: "Code", url: "https://antoyang.github.io/just-ask.html"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'Ethics and Bias', 'Large-Scale Training', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
Recent methods for visual question answering rely on large-scale annotated
datasets. Manual annotation of questions and answers for videos, however, is
tedious, expensive and prevents scalability. In this work, we propose to avoid
manual annotation and generate a large-scale training dataset for video
question answering making use of automatic cross-modal supervision. We leverage
a question generation transformer trained on text data and use it to generate
question-answer pairs from transcribed video narrations. Given narrated videos,
we then automatically generate the HowToVQA69M dataset with 69M
video-question-answer triplets. To handle the open vocabulary of diverse
answers in this dataset, we propose a training procedure based on a contrastive
loss between a video-question multi-modal transformer and an answer
transformer. We introduce the zero-shot VideoQA task and the VideoQA feature
probe evaluation setting and show excellent results, in particular for rare
answers. Furthermore, our method achieves competitive results on MSRVTT-QA,
ActivityNet-QA, MSVD-QA and How2QA datasets. We also show that our VideoQA
dataset generation approach generalizes to another source of web video and text
data. We use our method to generate the WebVidVQA3M dataset from the WebVid
dataset, i.e., videos with alt-text annotations, and show its benefits for
training VideoQA models. Finally, for a detailed evaluation we introduce iVQA,
a new VideoQA dataset with reduced language bias and high-quality manual
annotations. Code, datasets and trained models are available at
https://antoyang.github.io/just-ask.html
