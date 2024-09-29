---
layout: publication
title: Mgpt Few45;shot Learners Go Multilingual
authors: Shliazhko Oleh, Fenogenova Alena, Tikhonova Maria, Mikhailov Vladislav, Kozlova Anastasia, Shavrina Tatiana
conference: "Arxiv"
year: 2022
bibkey: shliazhko2022few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07580"}
tags: ['Attention Mechanism', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tokenization', 'Tools', 'Training Techniques', 'Transformer']
---
Recent studies report that autoregressive language models can successfully solve many NLP tasks via zero45; and few45;shot learning paradigms which opens up new possibilities for using the pre45;trained language models. This paper introduces two autoregressive GPT45;like models with 1.3 billion and 13 billion parameters trained on 60 languages from 25 language families using Wikipedia and Colossal Clean Crawled Corpus. We reproduce the GPT45;3 architecture using GPT45;2 sources and the sparse attention mechanism; Deepspeed and Megatron frameworks allow us to parallelize the training and inference steps effectively. The resulting models show performance on par with the recently released XGLM models by Facebook covering more languages and enhancing NLP possibilities for low resource languages of CIS countries and Russian small nations. We detail the motivation for the choices of the architecture design thoroughly describe the data preparation pipeline and train five small versions of the model to choose the most optimal multilingual tokenization strategy. We measure the model perplexity in all covered languages and evaluate it on the wide spectre of multilingual tasks including classification generative sequence labeling and knowledge probing. The models were evaluated with the zero45;shot and few45;shot methods. Furthermore we compared the classification tasks with the state45;of45;the45;art multilingual model XGLM. source code and the mGPT XL model are publicly released.
