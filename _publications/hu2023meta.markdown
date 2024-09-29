---
layout: publication
title: Meta45;learning Online Adaptation Of Language Models
authors: Hu Nathan, Mitchell Eric, Manning Christopher D., Finn Chelsea
conference: "Arxiv"
year: 2023
bibkey: hu2023meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15076"}
tags: ['GPT', 'Language Modeling', 'Pretraining Methods', 'Reinforcement Learning']
---
Large language models encode impressively broad world knowledge in their parameters. However the knowledge in static language models falls out of date limiting the models effective shelf life. While online fine45;tuning can reduce this degradation we find that naively fine45;tuning on a stream of documents leads to a low level of information uptake. We hypothesize that online fine45;tuning does not sufficiently attend to important information. That is the gradient signal from important tokens representing factual information is drowned out by the gradient from inherently noisy tokens suggesting that a dynamic context45;aware learning rate may be beneficial. We therefore propose learning which tokens to upweight. We meta45;train a small autoregressive model to reweight the language modeling loss for each token during online fine45;tuning with the objective of maximizing the out45;of45;date base question45;answering models ability to answer questions about a document after a single weighted gradient step. We call this approach Context45;aware Meta45;learned Loss Scaling (CaMeLS). Across three different distributions of documents our experiments find that CaMeLS provides substantially improved information uptake on streams of thousands of documents compared with standard fine45;tuning and baseline heuristics for reweighting token losses.
