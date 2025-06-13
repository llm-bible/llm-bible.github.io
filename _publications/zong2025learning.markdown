---
layout: publication
title: 'Evidencemap: Learning Evidence Analysis To Unleash The Power Of Small Language Models For Biomedical Question Answering'
authors: Chang Zong, Jian Wan, Siliang Tang, Lei Zhang
conference: "Arxiv"
year: 2025
bibkey: zong2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12746'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
When addressing professional questions in the biomedical domain, humans
typically acquire multiple pieces of information as evidence and engage in
multifaceted analysis to provide high-quality answers. Current LLM-based
question answering methods lack a detailed definition and learning process for
evidence analysis, leading to the risk of error propagation and hallucinations
while using evidence. Although increasing the parameter size of LLMs can
alleviate these issues, it also presents challenges in training and deployment
with limited resources. In this study, we propose EvidenceMap, which aims to
enable a tiny pre-trained language model to explicitly learn multiple aspects
of biomedical evidence, including supportive evaluation, logical correlation
and content summarization, thereby latently guiding a small generative model
(around 3B parameters) to provide textual responses. Experimental results
demonstrate that our method, learning evidence analysis by fine-tuning a model
with only 66M parameters, exceeds the RAG method with an 8B LLM by 19.9% and
5.7% in reference-based quality and accuracy, respectively.
