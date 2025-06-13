---
layout: publication
title: 'In-context Alignment: Chat With Vanilla Language Models Before Fine-tuning'
authors: Xiaochuang Han
conference: "Arxiv"
year: 2023
bibkey: han2023chat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04275"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
In this note, we explore inference-time alignment through in-context
learning. We consider a vanilla pretrained language model Llama-2 before any
fine-tuning and retrieve an average of 9 demonstration alignment examples when
the model is prompted to follow chat-style instructions. Compared to direct
prompting, the in-context alignment without changing model weights leads to a
7x increase in win-rate w.r.t. the text-davinci-003 model from OpenAI, making
the vanilla language model comparable to strong baselines with alignment
fine-tuning.
