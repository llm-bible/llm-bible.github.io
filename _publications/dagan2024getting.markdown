---
layout: publication
title: 'Getting The Most Out Of Your Tokenizer For Pre-training And Domain Adaptation'
authors: Dagan Gautier, Synnaeve Gabriel, Rozière Baptiste
conference: "Arxiv"
year: 2024
bibkey: dagan2024getting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01035"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Tokenization', 'Training Techniques']
---
Tokenization is an understudied and often neglected component of modern LLMs. Most published works use a single tokenizer for all experiments, often borrowed from another model, without performing ablations or analysis to optimize tokenization. Moreover, the tokenizer is generally kept unchanged when fine-tuning a base model. In this paper, we show that the size, pre-tokenization regular expression, and training data of a tokenizer can significantly impact the model's generation speed, effective context size, memory usage, and downstream performance. We train specialized Byte-Pair Encoding code tokenizers, and conduct extensive ablations on the impact of tokenizer design on the performance of LLMs for code generation tasks such as HumanEval and MBPP, and provide recommendations for tokenizer hyper-parameters selection and switching the tokenizer in a pre-trained LLM. We perform our experiments on models trained from scratch and from pre-trained models, verifying their applicability to a wide range of use-cases. We find that when fine-tuning on more than 50 billion tokens, we can specialize the tokenizer of a pre-trained LLM to obtain large gains in generation speed and effective context size.
