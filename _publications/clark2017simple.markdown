---
layout: publication
title: Simple And Effective Multi-paragraph Reading Comprehension
authors: Christopher Clark, Matt Gardner
conference: Arxiv
year: 2017
citations: 104
bibkey: clark2017simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1710.10723'}]
tags: [RAG]
---
We consider the problem of adapting neural paragraph-level question answering
models to the case where entire documents are given as input. Our proposed
solution trains models to produce well calibrated confidence scores for their
results on individual paragraphs. We sample multiple paragraphs from the
documents during training, and use a shared-normalization training objective
that encourages the model to produce globally correct output. We combine this
method with a state-of-the-art pipeline for training models on document QA
data. Experiments demonstrate strong performance on several document QA
datasets. Overall, we are able to achieve a score of 71.3 F1 on the web portion
of TriviaQA, a large improvement from the 56.7 F1 of the previous best system.