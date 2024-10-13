---
layout: publication
title: 'Probing Of Quantitative Values In Abstractive Summarization Models'
authors: White Nathan M.
conference: "Arxiv"
year: 2022
bibkey: white2022probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.00667"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Abstractive text summarization has recently become a popular approach, but
data hallucination remains a serious problem, including with quantitative data.
We propose a set of probing tests to evaluate the efficacy of abstract
summarization models' modeling of quantitative values found in the input text.
Our results show that in most cases, the encoders of recent SOTA-performing
models struggle to provide embeddings that adequately represent quantitative
values in the input compared to baselines, and in particular, they outperform
random representations in some, but surprisingly not all, cases. Under our
assumptions, this suggests that the encoder's performance contributes to the
quantity hallucination problem. One model type in particular, DistilBART-CDM,
was observed to underperform randomly initialized representations for several
experiments, and performance versus BERT suggests that standard pretraining and
fine-tuning approaches for the summarization task may play a role in
underperformance for some encoders.
