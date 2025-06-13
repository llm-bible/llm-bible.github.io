---
layout: publication
title: 'Dialoguellm: Context And Emotion Knowledge-tuned Large Language Models For Emotion Recognition In Conversations'
authors: Yazhou Zhang, Mengyao Wang, Youxi Wu, Prayag Tiwari, Qiuchi Li, Benyou Wang, Jing Qin
conference: "Arxiv"
year: 2023
bibkey: zhang2023context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.11374'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) and their variants have shown extraordinary
efficacy across numerous downstream natural language processing (NLP) tasks,
which has presented a new vision for the development of NLP. Despite their
remarkable performance in natural language generating (NLG), LLMs lack a
distinct focus on the emotion understanding domain. As a result, using LLMs for
emotion recognition may lead to suboptimal and inadequate precision. Another
limitation of LLMs is that they are typical trained without leveraging
multi-modal information. To overcome these limitations, we propose DialogueLLM,
a context and emotion knowledge tuned LLM that is obtained by fine-tuning LLaMA
models with 13,638 multi-modal (i.e., texts and videos) emotional dialogues.
The visual information is considered as the supplementary knowledge to
construct high-quality instructions. We offer a comprehensive evaluation of our
proposed model on three benchmarking emotion recognition in conversations (ERC)
datasets and compare the results against the SOTA baselines and other SOTA
LLMs. Additionally, DialogueLLM-7B can be easily trained using LoRA on a 40GB
A100 GPU in 5 hours, facilitating reproducibility for other researchers.
