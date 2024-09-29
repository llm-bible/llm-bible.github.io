---
layout: publication
title: 'Look Before You Speak: Visually Contextualized Utterances'
authors: Seo Paul Hongsuck, Nagrani Arsha, Schmid Cordelia
conference: "Arxiv"
year: 2020
bibkey: seo2020look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2012.05710"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
While most conversational AI systems focus on textual dialogue only conditioning utterances on visual context (when its available) can lead to more realistic conversations. Unfortunately a major challenge for incorporating visual context into conversational dialogue is the lack of large-scale labeled datasets. We provide a solution in the form of a new visually conditioned Future Utterance Prediction task. Our task involves predicting the next utterance in a video using both visual frames and transcribed speech as context. By exploiting the large number of instructional videos online we train a model to solve this task at scale without the need for manual annotations. Leveraging recent advances in multimodal learning our model consists of a novel co-attentional multimodal video transformer and when trained on both textual and visual context outperforms baselines that use textual inputs alone. Further we demonstrate that our model trained for this task on unlabelled videos achieves state-of-the-art performance on a number of downstream VideoQA benchmarks such as MSRVTT-QA MSVD-QA ActivityNet-QA and How2QA.
