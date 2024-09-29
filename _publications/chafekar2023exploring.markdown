---
layout: publication
title: Exploring Answer Information Methods For Question Generation With Transformers
authors: Chafekar Talha, Hussain Aafiya, Sharma Grishma, Sharma Deepak
conference: "Arxiv"
year: 2023
bibkey: chafekar2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03483"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
There has been a lot of work in question generation where different methods to provide target answers as input have been employed. This experimentation has been mostly carried out for RNN based models. We use three different methods and their combinations for incorporating answer information and explore their effect on several automatic evaluation metrics. The methods that are used are answer prompting using a custom product method using answer embeddings and encoder outputs choosing sentences from the input paragraph that have answer related information and using a separate cross45;attention attention block in the decoder which attends to the answer. We observe that answer prompting without any additional modes obtains the best scores across rouge meteor scores. Additionally we use a custom metric to calculate how many of the generated questions have the same answer as the answer which is used to generate them.
