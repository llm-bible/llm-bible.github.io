---
layout: publication
title: 'Fine Tuning LLM For Enterprise: Practical Guidelines And Recommendations'
authors: Mathav Raj J, Kushala Vm, Harikrishna Warrier, Yogesh Gupta
conference: "Arxiv"
year: 2024
bibkey: j2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10779"}
tags: ['RAG']
---
There is a compelling necessity from enterprises for fine tuning LLMs (Large
Language Models) o get them trained on proprietary domain knowledge. The
challenge is to imbibe the LLMs with domain specific knowledge using the most
optimial resource and cost and in the best possible time. Many enterprises rely
on RAG (Retrieval Augmented Generation) which does not need LLMs to be
ine-tuned but they are limited by the quality of vector databases and their
retrieval capabilities rather than the intrinsic capabilities of the LLMs
themselves. In our current work we focus on fine tuning LLaMA, an open source
LLM using proprietary documents and code from an enterprise repository and use
the fine tuned models to evaluate the quality of responses. As part of this
work, we aim to guide beginners on how to start with fine tuning an LLM for
documentation and code by making educated guesses on size of GPU required and
options that are available for formatting the data. We also propose pre
processing recipes for both documentation and code to prepare dataset in
different formats. The proposed methods of data preparation for document
datasets are forming paragraph chunks, forming question and answer pairs and
forming keyword and paragraph chunk pairs. For code dataset we propose forming
summary and function pairs. Further, we qualitatively evaluate the results of
the models for domain specific queries. Finally, we also propose practical
guidelines and recommendations for fine tuning LLMs.
