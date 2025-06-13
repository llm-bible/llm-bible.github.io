---
layout: publication
title: 'Fine-tuned Large Language Models (llms): Improved Prompt Injection Attacks Detection'
authors: Md Abdur Rahman, Fan Wu, Alfredo Cuzzocrea, Sheikh Iqbal Ahamed
conference: "Arxiv"
year: 2024
bibkey: rahman2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21337'}
tags: ['Security', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'BERT', 'Prompting', 'Ethics and Bias', 'Pretraining Methods']
---
Large language models (LLMs) are becoming a popular tool as they have
significantly advanced in their capability to tackle a wide range of
language-based tasks. However, LLMs applications are highly vulnerable to
prompt injection attacks, which poses a critical problem. These attacks target
LLMs applications through using carefully designed input prompts to divert the
model from adhering to original instruction, thereby it could execute
unintended actions. These manipulations pose serious security threats which
potentially results in data leaks, biased outputs, or harmful responses. This
project explores the security vulnerabilities in relation to prompt injection
attacks. To detect whether a prompt is vulnerable or not, we follows two
approaches: 1) a pre-trained LLM, and 2) a fine-tuned LLM. Then, we conduct a
thorough analysis and comparison of the classification performance. Firstly, we
use pre-trained XLM-RoBERTa model to detect prompt injections using test
dataset without any fine-tuning and evaluate it by zero-shot classification.
Then, this proposed work will apply supervised fine-tuning to this pre-trained
LLM using a task-specific labeled dataset from deepset in huggingface, and this
fine-tuned model achieves impressive results with 99.13% accuracy, 100%
precision, 98.33% recall and 99.15% F1-score thorough rigorous
experimentation and evaluation. We observe that our approach is highly
efficient in detecting prompt injection attacks.
