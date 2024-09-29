---
layout: publication
title: 'NSP-BERT: A Prompt-based Few-shot Learner Through An Original Pre-training Task--next Sentence Prediction'
authors: Sun Yi, Zheng Yu, Hao Chao, Qiu Hangping
conference: "Arxiv"
year: 2021
bibkey: sun2021nsp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.03564"}
tags: ['BERT', 'Few Shot', 'GPT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Using prompts to utilize language models to perform various downstream tasks also known as prompt-based learning or prompt-learning has lately gained significant success in comparison to the pre-train and fine-tune paradigm. Nonetheless virtually all prompt-based methods are token-level meaning they all utilize GPTs left-to-right language model or BERTs masked language model to perform cloze-style tasks. In this paper we attempt to accomplish several NLP tasks in the zero-shot scenario using a BERT original pre-training task abandoned by RoBERTa and other models--Next Sentence Prediction (NSP). Unlike token-level techniques our sentence-level prompt-based method NSP-BERT does not need to fix the length of the prompt or the position to be predicted allowing it to handle tasks such as entity linking with ease. Based on the characteristics of NSP-BERT we offer several quick building templates for various downstream tasks. We suggest a two-stage prompt method for word sense disambiguation tasks in particular. Our strategies for mapping the labels significantly enhance the models performance on sentence pair tasks. On the FewCLUE benchmark our NSP-BERT outperforms other zero-shot methods on most of these tasks and comes close to the few-shot methods.
