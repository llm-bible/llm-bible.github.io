---
layout: publication
title: Dynamar Dynamic Prompt With Mask Token Representation
authors: Sun Xiaodi, Rajagopalan Sunny, Nigam Priyanka, Lu Weiyi, Xu Yi, Zeng Belinda, Chilimbi Trishul
conference: "Arxiv"
year: 2022
bibkey: sun2022dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.02982"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Recent research has shown that large language models pretrained using unsupervised approaches can achieve significant performance improvement on many downstream tasks. Typically when adapting these language models to downstream tasks like a classification or regression task we employ a fine45;tuning paradigm in which the sentence representation from the language model is input to a task45;specific head; the model is then fine45;tuned end45;to45;end. However with the emergence of models like GPT45;3 prompt45;based fine45;tuning has been proven to be a successful approach for few45;shot tasks. Inspired by this work we study discrete prompt technologies in practice. There are two issues that arise with the standard prompt approach. First it can overfit on the prompt template. Second it requires manual effort to formulate the downstream task as a language model problem. In this paper we propose an improvement to prompt45;based fine45;tuning that addresses these two issues. We refer to our approach as DynaMaR 45;45; Dynamic Prompt with Mask Token Representation. Results show that DynaMaR can achieve an average improvement of 1037; in few45;shot settings and improvement of 3.737; in data45;rich settings over the standard fine45;tuning approach on four e45;commerce applications.
