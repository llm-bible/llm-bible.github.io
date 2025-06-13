---
layout: publication
title: 'Question: How Do Large Language Models Perform On The Question Answering Tasks? Answer:'
authors: Kevin Fischer, Darren Fürst, Sebastian Steindl, Jakob Lindner, Ulrich Schäfer
conference: "Arxiv"
year: 2024
bibkey: fischer2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12893'}
tags: ['Few-Shot', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have been showing promising results for various
NLP-tasks without the explicit need to be trained for these tasks by using
few-shot or zero-shot prompting techniques. A common NLP-task is
question-answering (QA). In this study, we propose a comprehensive performance
comparison between smaller fine-tuned models and out-of-the-box
instruction-following LLMs on the Stanford Question Answering Dataset 2.0
(SQuAD2), specifically when using a single-inference prompting technique. Since
the dataset contains unanswerable questions, previous work used a double
inference method. We propose a prompting style which aims to elicit the same
ability without the need for double inference, saving compute time and
resources. Furthermore, we investigate their generalization capabilities by
comparing their performance on similar but different QA datasets, without
fine-tuning neither model, emulating real-world uses where the context and
questions asked may differ from the original training distribution, for example
swapping Wikipedia for news articles.
  Our results show that smaller, fine-tuned models outperform current
State-Of-The-Art (SOTA) LLMs on the fine-tuned task, but recent SOTA models are
able to close this gap on the out-of-distribution test and even outperform the
fine-tuned models on 3 of the 5 tested QA datasets.
