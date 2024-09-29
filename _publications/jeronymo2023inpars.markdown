---
layout: publication
title: Inpars45;v2 Large Language Models As Efficient Dataset Generators For Information Retrieval
authors: Jeronymo Vitor, Bonifacio Luiz, Abonizio Hugo, Fadaee Marzieh, Lotufo Roberto, Zavrel Jakub, Nogueira Rodrigo
conference: "Arxiv"
year: 2023
bibkey: jeronymo2023inpars
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.01820"}
  - {name: "Code", url: "https://github.com/zetaalphavector/inPars/tree/master/tpu"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Recently InPars introduced a method to efficiently use large language models (LLMs) in information retrieval tasks via few45;shot examples an LLM is induced to generate relevant queries for documents. These synthetic query45;document pairs can then be used to train a retriever. However InPars and more recently Promptagator rely on proprietary LLMs such as GPT45;3 and FLAN to generate such datasets. In this work we introduce InPars45;v2 a dataset generator that uses open45;source LLMs and existing powerful rerankers to select synthetic query45;document pairs for training. A simple BM25 retrieval pipeline followed by a monoT5 reranker finetuned on InPars45;v2 data achieves new state45;of45;the45;art results on the BEIR benchmark. To allow researchers to further improve our method we open source the code synthetic data and finetuned models https://github.com/zetaalphavector/inPars/tree/master/tpu
