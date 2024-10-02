---
layout: publication
title: 'Porting Large Language Models To Mobile Devices For Question Answering'
authors: Fassold Hannes
conference: "Arxiv"
year: 2024
bibkey: fassold2024porting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15851"}
tags: ['Applications', 'Prompting', 'Tools']
---
Deploying Large Language Models (LLMs) on mobile devices makes all the capabilities of natural language processing available on the device. An important use case of LLMs is question answering, which can provide accurate and contextually relevant answers to a wide array of user queries. We describe how we managed to port state of the art LLMs to mobile devices, enabling them to operate natively on the device. We employ the llama.cpp framework, a flexible and self-contained C++ framework for LLM inference. We selected a 6-bit quantized version of the Orca-Mini-3B model with 3 billion parameters and present the correct prompt format for this model. Experimental results show that LLM inference runs in interactive speed on a Galaxy S21 smartphone and that the model delivers high-quality answers to user queries related to questions from different subjects like politics, geography or history.
